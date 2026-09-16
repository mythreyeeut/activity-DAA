class Solution {
    public int lengthOfLongestSubstring(String s) {
        int maxLength = 0;
        int left = 0;

        for (int right = 0; right < s.length(); right++) {
            for (int i = left; i < right; i++) {
                if (s.charAt(i) == s.charAt(right)) {
                    left = i + 1;
                    break;
                }
            }

            maxLength = Math.max(maxLength, right - left + 1);
        }

        return maxLength;
    }
}

class Solution:
    def minimumOperations(self, nums: List[int]) -> int:
        x = 0
        for i in nums:
            remainder = i % 3
            if remainder == 1:
                x += 1
            elif remainder == 2:
                x += 1
        return x

public:: true

- You're becoming aware of the patriarchy's toxic impact on society, and you're someone whose identity (perhaps you're a white man) gives you some measure of free power and privilege compared to others.
- ## Problem
	- Instead of wallowing in guilt, or watching from the sidelines, you want to use your power for good. But how can you help?
- ## Tensions
	- Fear of breaching norms of political correctness can make men afraid of appearing patronizing towards women and other under-represented minorities by offering help.
		- [[You can't say anything these days]]
	- Patriarchy shames men into conforming with a masculine stereotype that would never challenge patriarchal norms. It can be daunting to break out of this.
		- [[Stick your neck out]]
	- *But:*
		- Women and other minorities are tired of doing the labour of educating people about the patriarchy and its impact on them.
			- [[What did they already say?]]
		- Because patriarchy puts power into the hands of men, nothing will change without them.
- ## Solution
	- Learn the patterns in this language!
	- Here's a list:
	- | Pattern      | **Problem** | Test Text     |
	  | :---        |    :----:   |          ---: |
	  | [[Create Space for Dialogue]]      | **Title**       | Here's this   |
	  | [[Know their trigger phrases]]   | **Title**        | And more      |
- query-properties:: [:page]
  #+BEGIN_QUERY
  {
     :title "Patterns"
     :query [:find (pull ?p [*])
                  :where [?p :page/name "create space"]]
  }
  #+END_QUERY
-
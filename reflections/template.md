# Day XX — [Topic Title]

**Date:** YYYY-MM-DD  
**Participant:** Phanie  

---

## 1. Problem Summary
Briefly describe the challenge or problem statement.  
Include key requirements (e.g., what data needed to be extracted, filtered, or aggregated).

> Example:  
> Retrieve all customers who made more than three purchases in the last month.

---

## 2. Approach
Explain the logic behind your SQL solution.  
Outline your thought process, key clauses used, and why you chose that structure.

**Example:**  
- Joined `orders` and `customers` on `customer_id`  
- Used `GROUP BY` with `COUNT(*)` to find repeat customers  
- Filtered results with `HAVING COUNT(*) > 3`

---

## 3. Challenges Encountered
Note any issues or confusion faced while solving.  
This can include syntax errors, inefficient queries, or logical mistakes.

**Example:**  
Initially used `WHERE COUNT(*) > 3`, which caused an error — realized `HAVING` must be used with aggregates.

---

## 4. Optimization and Alternative Solutions
Reflect on how the query could be improved.  
If you or your partner had different solutions, describe and compare them here.

**Example:**  
My buddy used a subquery instead of a `JOIN`. Their solution was more concise but slightly less readable.

---

## 5. Key Takeaways
Summarize what you learned today — both technically and conceptually.

**Example:**  
- Reinforced the difference between `WHERE` and `HAVING`  
- Learned to alias subqueries for better readability  
- Discovered that PostgreSQL allows `FILTER()` with aggregates

---

## 6. Next Focus
Mention what you’d like to focus on next or what concept needs review.

**Example:**  
Practice more on subqueries and explore CTEs for complex filters.

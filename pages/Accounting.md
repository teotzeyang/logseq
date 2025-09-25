icon:: 💵
type:: [[Knowledge Base]]
description:: Knowledge base of all foundational accounting papers.

- PFF
	- PFF topics
	  collapsed:: true
		- Financial reporting framework
			- [[Financial statements]]
			- [[Conceptual framework]]
			- [[Professional ethics]]
		- Elements of financial statments
			- Assets
				- [[PPE]]
				- [[Inventory]]
				- [[Investment property]]
				- [[Intangible assets]]
			- Liabilities
				- [[Leases]]
				- [[Contract]]
				- [[Financial liabilities]]
					- [[Bonds]]
				- [[Income tax]]
				- [[Provisions]]
				- [[Contingent liabilities]]
			- [[Impairment]]
		- Preparation of financial statements
			- Statement of [[Comprehensive income]]/[[SPL]]
			- Statement of [[Financial position]]
			- Statement of [[Cash flows]]
			- Statement of [[Changes in equity]]
		- Other standards
			- [[Accounting policies, estimate changes and errors]]
			- [[Events after reporting period]]
			- [[Foreign currency]]
	- query-properties:: [:page]
	  query-sort-by:: page
	  query-sort-desc:: false
	  collapsed:: true
	  #+BEGIN_QUERY
	  {
	  :title ["PFF papers"]
	  :query [:find (pull ?p [*])
	    :where
	     [?p :block/name ?name]
	     [(str "(?i)" "PFF") ?pattern]
	     [(re-pattern ?pattern) ?q]
	     [(re-find ?q ?name)]
	   ]
	  }
	  #+END_QUERY
- ASF
	- ASF topics #WIP
	  id:: 68c986e5-0511-4a4e-bdc6-8c78adebe1d6
	  collapsed:: true
		- Regulatory frameworks
			- Role of boards and audit committees
		- Laws and regulations
			- [[Audit responsibilities]]
			- How to deal with non-compliance
		- Practice management
			- Code of professional conduct and ethics
				- Money laundering guidelines
				- Identify ethical issues and safeguards
				- Course of action when discovering breaches
			- Professional responsibility
				- Responsibilities related to fraud and error
				- [[Communication of deficiency]]
			- [[Quality management]]
				- Engagement quality review
			- Appointment of auditors
				- Considerations and procedures related to accepting/continuing engagements
		- Planning audit
			- Audit planning
				- Understanding financial reporting framework
				- Analytical procedures
				- [[Assertion]]
			- Evaluation of internal controls
				- Revenue, purchases, expenditure, PPE, inventory, payroll, and cash
				- Tests of controls against misstatements
			- Materiality
				- Audit risks
			- IT
				- IT controls and effect on auditing
		- Performing audit
			- Audit evidence
				- Identifying appropriate evidence to support assertions
				- [[Audit documentation]]
			- [[Audit procedures]]
				- [[Test of details]]
				- Applying audit procedures for all transactions
				- Explain risks concerning third-parties
			- [[Expert engagement]]
				- Circumstances where expert opinion is required
				- Work to be done when expert is involved
			- Evaluation and review
				- Explain use of analytical procedures
		- Reporting
			- [[Auditor's report]]
				- Statutory audit report
				- Determining key audit matters
				- Proposed audit opinion
			- Assurance other than audit
				- Main service categories
			- Other reports
				- Professional accountant's report
				- Negative assurance
	- query-properties:: [:page]
	  query-sort-by:: page
	  query-sort-desc:: false
	  collapsed:: true
	  #+BEGIN_QUERY
	  {
	  :title ["ASF papers"]
	  :query [:find (pull ?p [*])
	    :where
	     [?p :block/name ?name]
	     [(str "(?i)" "ASF") ?pattern]
	     [(re-pattern ?pattern) ?q]
	     [(re-find ?q ?name)]
	   ]
	  }
	  #+END_QUERY
- AFF
	- AFF topics #WIP
	  collapsed:: true
		- [[Related party disclosure]]
		- [[Intangible assets]]
		- [[Impairment]]
		- [[Contract]]
		- [[Foreign currency]]
		- [[Consolidated financial statements]]
		- [[Business combination]]
		- [[Non-current asset disposal]]
	- query-properties:: [:page]
	  query-sort-by:: page
	  query-sort-desc:: false
	  collapsed:: true
	  #+BEGIN_QUERY
	  {
	  :title ["AFF papers"]
	  :query [:find (pull ?p [*])
	    :where
	     [?p :block/name ?name]
	     [(str "(?i)" "AFF") ?pattern]
	     [(re-pattern ?pattern) ?q]
	     [(re-find ?q ?name)]
	   ]
	  }
	  #+END_QUERY
- ADF
	- ADF topics #WIP
		- Accounting as a tool
			- [[Primary responsibilities]]
			- [[Integrated reporting]]
			- [[Management accounting]]
			- [[Throughput accounting]]
			- [[Merchandising, Manufacturing and Service]]
		- Cost analysis
			- [[Contribution margin]]
			- [[Breakeven]]
			- [[Relevant cost]]
			- [[Variable costing]]
			- [[Target costing]]
			- [[Absorption costing]]
		- Performance analysis
			- [[Budget]]
			- [[Variance]]
			- [[Standard cost]]
			- [[Performance measures]]
		- Business [[Decision making]]
			- Responsibility centres
				- [[Cost centre]]
				- [[Profit centre]]
				- [[Investment centre]]
				- [[Transfer pricing]]
			- [[Quality, cost, time triangle]]
		- Strategic management
			- Models
				- [[Porter's generic strategies]]
				- [[Porter's 5 forces]]
				- [[Ansoff's growth matrix]]
				- [[PESTLE]]
			- [[Balanced scorecard]]
			- [[Key performance indicators]]
			- [[Residual income]]
			- [[Sustainability]]
	- query-sort-by:: page
	  query-sort-desc:: false
	  query-properties:: [:page]
	  collapsed:: true
	  #+BEGIN_QUERY
	  {
	  :title ["ADF papers"]
	  :query [:find (pull ?p [*])
	    :where
	     [?p :block/name ?name]
	     [(str "(?i)" "ADF") ?pattern]
	     [(re-pattern ?pattern) ?q]
	     [(re-find ?q ?name)]
	   ]
	  }
	  #+END_QUERY
- Question bank
	- PFF
	  collapsed:: true
		- [[PFF D17]]
		  collapsed:: true
			- Q1
			- Q2
			- Q3
		- [[PFF J18]]
		  collapsed:: true
			- Q1
			- Q3
		- [[PFF D18]]
		  collapsed:: true
			- Q1
			- Q2
			- Q3
			- Q4
		- [[PFF J19]]
		  collapsed:: true
			- Q2
			- Q3
			- Q4
		- [[PFF D19]]
		  collapsed:: true
			- Q2
			- Q4
		- [[PFF J20]]
		  collapsed:: true
			- Q2
			- Q4
		- [[PFF D20]]
		  collapsed:: true
			- Q2
			- Q4
		- [[PFF J21]]
		  collapsed:: true
			- Q1
			- Q2
			- Q3
			- Q4
		- [[PFF D21]]
		  collapsed:: true
			- Q1
		- [[PFF J22]]
		  collapsed:: true
			- Q1
			- Q2
		- [[PFF D22]]
		  collapsed:: true
			- Q1
			- Q2
			- Q4
		- [[PFF J23]]
		  collapsed:: true
			- Q4
		- [[PFF D23]]
		  collapsed:: true
			- Q3
		- [[PFF J24]]
		  collapsed:: true
			- Q1
	- ASF
	  collapsed:: true
		- [[ASF J21]]
		  collapsed:: true
			- Q3
			- Q4
		- [[ASF D21]]
		  collapsed:: true
			- Q1
			- Q2
			- Q3
			- Q4
		- [[ASF J22]]
		  collapsed:: true
			- Q1
			- Q3
			- Q4
		- [[ASF D22]]
		  collapsed:: true
			- Q1
			- Q2
			- Q4
		- [[ASF J23]]
		  collapsed:: true
			- Q2
			- Q3
			- Q4
		- [[ASF D23]]
		  collapsed:: true
			- Q1
			- Q2
			- Q3
			- Q4
		- [[ASF J24]]
		  collapsed:: true
			- Q1
			- Q2
			- Q3
	- AFF
	  collapsed:: true
		- [[AFF D24]] #WIP
		  collapsed:: true
			- Q1
			- Q2
			- Q3
			- Q4
		- AFF Tutorials #WIP
		  collapsed:: true
			- Consolidated financial statements (3)
				- Q1
				- Q2
			- Consolidated financial statements (2)
				- Q1
				  collapsed:: true
					- [[Consolidated financial statements]] journal entry from statement of [[Comprehensive income]] and statement of [[Financial position]]
						- Parent to subsidiary
						  collapsed:: true
							- Elimination of loan/payable balance
								- Dr Loan payables, Cr Loan receivables
							- Elimination of interest
								- Dr Other income, Cr Operating expense
						- Goodwill impairment
						  collapsed:: true
							- Dr Retained profit (if from prior period), Dr Impairment loss, Cr Goodwill
						- No statement of [[Changes in equity]] means don't need to include OCI in records
					- If non-controlling interest is measured based on fair value and subsidiary shares are freely traded:
						- Non-controlling interest based on share price of subsidiary at acquisition date
						- Goodwill on consolidation might not be proportional to % share of net assets
						- A portion of the goodwill is attributable to non-controlling interest and impairment will be charged to non-controlling interest
						- Goodwill impairment charged to non-controlling interest will reduce the post-acquisition retained profits for prior periods and the share of profits for current year
				- Q2
				- Q3
				- Q4
	- ADF
	  collapsed:: true
		- [[ADF J18]] Q4
		- [[ADF D18]] Q2
		- [[ADF D19]] Q4
		- [[ADF J21]] Q1
		- [[ADF J20]] Q1
		- [[ADF J22]] Q3
		- [[ADF D22]] Q2
		- [[ADF D22]] Q3
		- [[ADF D23]] Q4
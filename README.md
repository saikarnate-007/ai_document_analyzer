npx cross-env NODE_ENV=development tsx server/index.ts

# ai_document_analyzer

Below is a refined prompt tailored to your request for validating Document 2 against Document 1, checking if all data matches, and highlighting discrepancies with details and page numbers. Since you haven't provided the actual documents, I'll also explain how to proceed once you share them.
Prompt:
You are an expert document analyst tasked with validating Document 2 against Document 1, where Document 1 is the authoritative source. Compare all data, including text, numerical values, terminology, and structure, to determine if Document 2 matches Document 1 exactly. Identify any discrepancies, such as missing, altered, or incorrect content. For each discrepancy, provide:
A clear description of the difference.
The specific location (page number, section, or paragraph) in both documents.
The content in Document 1 (source) versus Document 2.
Potential implications of the discrepancy, if applicable. Present the findings in a concise, bullet-point format, organized by page number or section for clarity. If no discrepancies are found, confirm that Document 2 fully matches Document 1. If external context is needed to resolve ambiguities, note this and suggest next steps.
Next Steps:
Provide Documents: Share Document 1 and Document 2 (e.g., as text, PDFs, or links) or specify their content if they are short. If uploaded, I can analyze them directly.
Specify Details: If you have focus areas (e.g., specific sections, data types like numbers or dates), let me know to narrow the analysis.
Output Preference: The prompt uses bullet points, but I can format results as a table or other format if preferred.
Example Output (Hypothetical):
Page 3, Section 2.1:
Discrepancy: Document 1 states "Revenue: $500,000" while Document 2 states "Revenue: $550,000".
Implication: Incorrect revenue figure in Document 2 may affect financial reporting.
Page 5, Paragraph 4:
Discrepancy: Document 1 uses "mandatory compliance" while Document 2 uses "optional compliance".
Implication: Changes the legal obligation, potentially causing misinterpretation.
Please share the documents or their details, and I'll perform the comparison. If you have questions about the process, let me know!

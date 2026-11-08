# AI Voice Agent Testing – Test Case Documentation

## 1. Project Overview

This project demonstrates sample test scenarios for validating AI-powered voice agents used in customer communication and fintech collections workflows.

Objective: Ensure that AI voice agents respond accurately, follow configured conversational instructions, handle interruptions, and maintain natural conversations.

## 2. Test Scenarios

| TC ID | Test Scenario | Expected Result |

| TC_001 | Greeting Validation | Agent should greet the customer professionally. |
| TC_002 | Call Purpose Validation | Agent should clearly explain the reason for calling. |
| TC_003 | Borrower Identification | Agent should verify the correct person before discussing account details. |
| TC_004 | Wrong Number Handling | Agent should politely close the call when the person is not the borrower and has no relevant relationship. |
| TC_005 | Interruption Handling | Agent should pause and respond appropriately when the customer interrupts. |
| TC_006 | Language Switching | Agent should handle supported language changes correctly. |
| TC_007 | Payment Commitment | Agent should capture the customer's payment commitment accurately. |
| TC_008 | Payment Link Handling | Agent should provide the correct payment link when requested. |
| TC_009 | No Response Handling | Agent should follow the configured silence-handling instructions. |
| TC_010 | Unexpected Response Validation | Agent should not generate irrelevant or unconfigured responses. |
| TC_011 | Voice Quality Validation | Agent's voice should be clear, stable, and understandable throughout the call. |
| TC_012 | Call Closing Validation | Agent should close the conversation politely and appropriately. |

## 3. Detailed Test Cases

### TC_001 – Greeting Validation
- Test Objective: Verify the opening greeting.
- Test Steps:
  1. Initiate a test call.
  2. Listen to the agent's opening statement.
  3. Verify the greeting against the configured prompt.
- Expected Result: Agent should provide the correct greeting without unnecessary or unrelated words.

### TC_002 – Interruption Handling
- Test Objective: Verify the agent's ability to handle customer interruptions.
- Test Steps:
  1. Initiate a test call.
  2. Allow the agent to start speaking.
  3. Interrupt the agent while it is speaking.
  4. Observe the agent's response.
- Expected Result: Agent should acknowledge the interruption, understand the customer's input, and continue the conversation appropriately.

### TC_003 – Language Switching
- Test Objective: Verify multilingual conversation handling.
- Test Steps:
  1. Start a conversation in English.
  2. Switch to a supported language.
  3. Observe the agent's language and pronunciation.
- Expected Result: Agent should respond in the selected supported language with accurate and natural wording.

### TC_004 – Payment Commitment Validation
- Test Objective: Verify payment commitment handling.
- Test Steps:
  1. Initiate a test conversation.
  2. Provide a payment commitment.
  3. Mention a payment date and time.
  4. Verify the agent's confirmation.
- Expected Result: Agent should accurately capture and confirm the payment commitment without changing the customer's details.

### TC_005 – Voice Quality Validation
- Test Objective: Identify voice-quality issues.
- Test Steps:
  1. Initiate a test call.
  2. Listen to the agent throughout the conversation.
  3. Check for voice breaking, distortion, unclear pronunciation, and unexpected pauses.
- Expected Result: Agent's voice should remain clear and consistent throughout the call.

## 4. Defect Reporting Format

| Field | Description |

| Bug ID | Unique defect reference |
| Test Case ID | Related test case |
| Issue Title | Short description of the issue |
| Steps to Reproduce | Steps to reproduce the issue |
| Expected Result | Intended agent behaviour |
| Actual Result | Observed agent behaviour |
| Severity | Critical / High / Medium / Low |
| Status | Open / In Progress / Fixed / Retested |

## 5. Testing Summary

The above scenarios cover important quality checks for AI voice agents, including conversational accuracy, prompt adherence, interruption handling, multilingual responses, payment commitment handling, and voice quality.

Note: These are sample test cases created for portfolio demonstration. Actual execution results should be recorded only after testing.

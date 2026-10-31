# EX-02-Cross-Platform-Prompting-Evaluating-Diverse-Techniques-in-AI-Powered-Text-Summarization
NAME: SAMYUKTHA.S

REG.NO:212225040363
## AIM
To evaluate and compare the effectiveness of prompting techniques (zero-shot, few-shot, chain-of-thought, role-based) across different AI platforms (e.g., ChatGPT, Gemini, Claude, Copilot) in a specific task: text summarization.

## Scenario:
You are part of a content curation team for an educational platform that delivers quick summaries of research papers to undergraduate students. Your task is to summarize a 500-word technical article on "The Basics of Blockchain Technology" using multiple AI platforms and prompting strategies.

Your goal is to determine which combination of prompting technique + platform provides the best summary in terms of:

Accuracy

Coherence

Simplicity

Speed

User experience

## Prompts
## 1. Basic Prompt 

Create a weekly study timetable for a college student who wants to prepare for five different subjects. 

The timetable should: 

Include all five subjects. 

Allocate sufficient time for each subject. 

Include short breaks between study sessions. 

Provide time for revision. 

Maintain a balanced daily study schedule. 

Present a simple and practical timetable that a college student can follow. 

## 2. Role Prompt 

Assume you are an experienced academic planner and student productivity coach. 

Create a weekly study timetable for a college student preparing for five different subjects. 

The timetable should: 

Distribute study hours equally according to subject difficulty. 

Include focused study sessions and short breaks. 

Provide separate time for learning new topics and revising completed topics. 

Include a daily self-assessment session. 

Help students improve their time management and academic performance. 

Make the timetable realistic, organized, and easy to follow. 

## 3. Context Prompt 

You are helping a second-year Computer Science Engineering student prepare for upcoming semester examinations. 

The student has five subjects: Java Programming, Computer Networks, Machine Learning, Computer Architecture, and Mathematics. 

The student attends college during the daytime and has approximately four hours available for studying in the evening. The student finds some subjects difficult and wants to complete the syllabus before the examinations. 

Create a personalized weekly study timetable. 

The timetable should: 

Give more preparation time to difficult subjects. 

Include all five subjects throughout the week. 

Divide the syllabus into manageable study sessions. 

Include revision and practice questions. 

Provide sufficient breaks and rest time. 

Make the timetable suitable for a college student's daily routine. 

## 4. Constraint Prompt 

Act as a professional academic planner and create a personalized weekly study timetable for a second-year Computer Science Engineering student preparing for semester examinations. 

The student has five subjects: Java Programming, Computer Networks, Machine Learning, Computer Architecture, and Mathematics. 

Follow these conditions strictly: 

The student has only four hours available for studying each evening. 

The timetable must cover all five subjects. 

Allocate more time to difficult subjects. 

Include a maximum of two hours for one continuous study session without a break. 

Include at least one short break between study sessions. 

Reserve time for solving programming problems and numerical questions. 

Include regular revision of previously studied topics. 

Keep Sunday comparatively flexible for revision and pending topics. 

Avoid creating an unrealistic or overloaded timetable. 

Prepare a practical schedule that improves consistency, time management, and examination preparation. 

## 5. Output Format Prompt 

Assume you are an expert academic planner and student productivity coach. 

Create a personalized weekly study timetable for a second-year Computer Science Engineering student preparing for semester examinations. 

Student Details: 

Subjects: Java Programming, Computer Networks, Machine Learning, Computer Architecture, and Mathematics. 

Available Study Time: Four hours every evening. 

Preparation Level: Basic understanding of all subjects. 

Goal: Complete the syllabus, improve subject knowledge, and prepare effectively for examinations. 

Present the final output using the following structure: 

1. Student Study Plan: 

Briefly explain the overall weekly preparation strategy. 

2. Weekly Timetable: 

Create a table containing: 

Day 

Study Time 

Subject 

Topic to Study 

Break Time 

3. Subject Priority: 

Identify difficult subjects and explain how additional preparation time is allocated. 

4. Daily Study Activities: 

Include concept learning, programming practice, problem-solving, and revision. 

5. Weekly Revision Plan: 

Explain how students can revise all five subjects at the end of the week. 

6. Productivity Tips: 

Provide five practical tips to maintain consistency and avoid distractions. 

Additional Instructions: 

Follow the four-hour daily study limit. 

Include appropriate breaks. 

Keep the schedule realistic and flexible. 

Use simple English. 

Present information in an organized and student-friendly manner. 

Avoid unnecessary explanations. 

The final output should be practical enough for a college student to follow throughout the examination preparation period. 

## Output
## 1. Basic Prompt – Summary
The AI generated a simple weekly study timetable covering five subjects. It allocated study hours, included short breaks, and provided revision time. The output was easy to understand and suitable for students who wanted to organize their daily study activities.

## BASIC PROMPT – CHATGPT VS GEMINI

Evaluation Criteria    ChatGPT       Gemini
Accuracy               High          High
Coherence              Good          Good
Simplicity             Excellent     Excellent
Speed                  Very Fast     Very Fast
User Experience        Excellent     Very Good

## 2. Role Prompt – Summary
The AI acted as an experienced academic planner and student productivity coach. It created a structured timetable by considering subject difficulty, study sessions, revision, and self-assessment. The output focused on improving students' time management and academic performance.

## ROLE PROMPT – GEMINI VS DEEPSEEK

Evaluation Criteria    Gemini        DeepSeek
Accuracy               High          High
Coherence              Excellent     Good
Simplicity             Excellent     Good
Speed                  Very Fast     Fast
User Experience        Excellent     Very Good

## 3. Context Prompt – Summary
The AI considered the background of a second-year Computer Science Engineering student preparing for semester examinations. It included five subjects, four hours of evening study time, and the student's basic preparation level. The generated timetable provided a personalized study schedule with practice sessions and revision.

## CONTEXT PROMPT – DEEPSEEK VS CLAUDE

Evaluation Criteria    DeepSeek      Claude
Accuracy               High          High
Coherence              Excellent     Excellent
Simplicity             Good          Excellent
Speed                  Fast          Fast
User Experience        Very Good     Excellent

## 4. Constraint Prompt – Summary
The AI generated a practical study timetable by following specific conditions and limitations. It maintained the four-hour daily study limit, included appropriate breaks, allocated additional time to difficult subjects, and provided revision sessions. The schedule avoided excessive workload and encouraged consistent preparation.
CONSTRAINT PROMPT – CLAUDE VS PERPLEXITY

## Evaluation Criteria    Claude        Perplexity
Accuracy               High          High
Coherence              Excellent     Good
Simplicity             Excellent     Very Good
Speed                  Fast          Very Fast
User Experience        Excellent     Very Good

## 5. Output Format Prompt – Summary
The AI generated a complete and well-organized academic study plan using the specified output format. It included a weekly timetable, subject priorities, daily study activities, a weekly revision plan, and productivity tips. The final output was structured, informative, and easy for students to follow.

## OUTPUT FORMAT PROMPT – PERPLEXITY VS CHATGPT

Evaluation Criteria    Perplexity    ChatGPT
Accuracy               High          High
Coherence              Good          Excellent
Simplicity             Excellent     Excellent
Speed                  Very Fast     Very Fast
User Experience        Very Good     Excellent



## Result
Thus the prompts using different prompt structures executed successfully.



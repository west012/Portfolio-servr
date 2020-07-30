psql -h portfolio-instance.ccsht2sj640l.us-west-2.rds.amazonaws.com -p 5432 -U postgres


CREATE TABLE projects (
    name VARCHAR(255),
    url VARCHAR(255),
    description VARCHAR(255),
    techUsed VARCHAR(255),
    imageURL VARCHAR(255),
    id serial PRIMARY KEY
);

DELETE FROM projects WHERE id = ;

INSERT INTO projects (name, url, description, techUsed, imageURL) VALUES ('Calculator', 'https://west012.github.io/sampleComplexCalculator/', 'Project showing implementation for arithmetic',' ','shorturl.at/aHPQ5');
            imgUrl: 'https://lh3.googleusercontent.com/ayZ2Lt9JU92sfGe5rO9CoxS7M_a0FZKhUkw9yHJwvOm5qIY742hmBNf4ItXNxsjDZvMI1qMrH7LxezZJMn6lQsNhk-a9YwXJTiotehc9jyVmHqPHMV7xPiPwD5JirXyomZIjUj2kshHevVU1xZ1DETU53nr_gTakaDn5f3lY1iIGotTXMDvX7YsWKHHYudOI0EvVPUMg7JnHUJx-nRCchUBFsS2532ueiT9Cni6BPHYW3v7gmCkUxIFPIH3CVblJVWt2gRGfSkNKYDJedW8vbupLal8sI6iBnJUzESSgRRN113uaVv-Td1NWgRTPu_5xEXCkDT0ImJqhyQDxvqbmSKTf4ZNYxPP4z1UhJwBwgOlwsyeKtNRscYpEbTxY9iYN450WNA-h7bPNIKFXaVPXpWlUL1BXkFCREXUfI2IzippRz7efw4pY6Vl-Tobhljra5gkXMfGYw16OAy5yelMFipmxg3Hz1HIYkmSFmOpky-uFL3uWkRFJ7WbAEVCbhvNnZhmuPKX25yoD1tzvi9LW6i4UlBiZK1t24GEs8vJiJaLk2kliHBokJH0akuvidYpgM3KKDtVDD7qHOqAeEzfGSmanfYDaAHfik8QlR9fsOoSCANNkpJ37lYoPJvn2zcgm8Ewxk9PA4NZ5l4r2zKKUFajnSOX2fciK2jN460iI2wWDwvLItr52kN1QloP9=w618-h782-no?authuser=0', 

INSERT INTO projects (name, url, description, techUsed, imageURL) VALUES ('NOTflix API', 'https://west012.github.io/NOTNetflix-API/', 'Scrubbing IMDB database for Movies',' ','shorturl.at/rtHX0');
            imgUrl: 'https://lh3.googleusercontent.com/VDbNM4PSaG5tXH_4RflFomESpysgMga3p__dwaS7yaJLV5i0LTWqJ4fHrz2iLIlkx0mq0xxIMAW_0bJa6VAq2tgtvMbsSCf5MPit1VTOCiXBU1zkdCGkl7mcBSL5uu0tGkPzblIcR51KudHIB-c_7wjLfPuQDXEECEqKNTnqOZPa8Vb5DAlT0CTcomZG27xO-jjRtYGLPPiK7AuoVDunZqDntVgk4lbqlaBK9kVhdblrNMK-GLhO1R3YovgOJSt6g04VWXheNmMMfCvXPr1vjiPHOz6rgKzAGoHQFhSWW_gDYJbLxBTMRjTThbILvQTYfuR7Msqz3wj70J66oV_De8TF-GUp_a6S8EE99w9rTc63H6XXjWp5tPc5-ANLaTen2pPDTwllQJkoeI3YveL6vrY6n-diT-6fuhU0eCezzhbEC5qNC55xo6WfIOqwPy_FnHUblobqLpv2xPEC4ZqtLMy_2y9nidUV1IPDyD_jSLQlb5fetv9QZBpFCsqKdTuCdR6-MMcmGxfm-u4aN72Vc9052CPHR7wr3DUB2FyzrDATbM7v-PzbY3MWj_qt5O-4lCX7Pa8vNhH_MlbbkBtJfJPJ-1JALJhOqJ9zZTmjSqdKYc7C8UbbpMHr2biSeNf3moYGso3vLztC5aXkWEVKIxzV4oVi2ZpuX8b7Ekn6vMxPl3n_zT8ezsbxRxSi=s250-k-rw-no', shorturl.at/rtHX0

INSERT INTO projects (name, url, description, techUsed, imageURL) VALUES ('Minesweeper Game', 'https://west012.github.io/Canvas-Game/', 'Simple game using Canvas and Arithmetic',' ','shorturl.at/aeflm');
            imgUrl: 'https://lh3.googleusercontent.com/ZDwC_dFcC5pKyxi2aqEInuuA66JjP92pC4S5Cl-HNtiUMj4pu7SsFIMqLx9NnceB3c0V-Kwpo2_v_yOB1NDCzk4yOYfFfRXglLVmwqP15m_W1ek0PbdgExasbXlB-xM0c2SGV52SNWQ48O833ElBCT9Rv2ok_KEFha_6uTj2IsTanGMTHv1LXUbvqH7uPvDTkCYz1Ok6zBgbV9PkjpOZYGBKyC9C5q-R7k4zXB43FmSb_OL6C1AUOJDpLNq0Lu6L8rxw16vyqWALmmaVWZslMZ42juSzwQPF-WMdzBu9uC-HFk_IIiXzohw_El6kKh6jopWkuBX6LEBOBPQ3Dryso1RouuSyN3xfcyQNVgPJcPyxNsZ5IKIhFehUt5LOG2feL3tiMh6U7ZguHye01XsNH0Q-R0r_KTMMqA78Z-GVfB0SNKLa7_t6h9LO1IUycHKz5_Z5bcFXUC8hzEE9UNMpPItykNuat5W2wAe8dMMmYhIBKxeecvlqUBXWRYk2rbdEmS1sbkIGe8n2HibDHsLWJBHbELe5Re15M5VfoefQ_l4fadjnc1679eXMnh8lXB3fWBsNAagOJPfi20lR1Xv1x3INFkdsm-3woogzXPntN8HRLm_ga2Wm709fxjgE16bxTUgb5Th0N5SPIdC79sh7Gb6FdQ7676Red2dDFrDM-7ilo2MBF3_DHpsNz1iQ=w912-h621-no?authuser=0', 


INSERT INTO projects (name, url, description, techUsed, imageURL) VALUES ('(CRUD) Create, Read, Update, Delete', ' ', 'Excercising SQL skills',' ','shorturl.at/gFU14');

imgUrl: 'https://lh3.googleusercontent.com/0FASFQO-jmZDpZ0u5LtCDjTCp1yvY6pGUEk-5R8KGpW5vOMYHu2jjWPRsTuacG3r1s1YyVf5VJshhpSXAaG70FCul5h1KP7BKtO6gF9UH9ts9AasNJCikQaBKTas7L_Xp9vfcHGkTUeZQqri8aB_rdA-Afi38sROEUSzhZEdO7Y5nUuFCi3n4Kd4VFu3qGHIaIJwTyjK3G6VXZGg-wmNzSwWxJdw0gOxfpzkaLqeaIr3428rIzsNjfZ7JcLCflv5CZIje0OFFrUP1ujH0f9nRtSGrbvKQY2G0BehBWQyQZ_268YrWsZ52pjn5cEbfgi-nBd8huYnmiTzDaDfxh3PpE31nk-mmvA8vPjQvYp0AqFEvySdZz5XO8OxiAPdpLMP1ItmrZ7iOvdsdaE5Lz0xk70hBFqLqaHZvhvuNVlzCY-w1Z_XH5suW7JQBbqhVhIJLwD8oTKkfbD3tVXN2qzlcKSf3QCYgPrlbpWbecTb5uembQ5bWD4Zy1fhKdfJjdKOtPqq9DZMBdE9R9_tbehgD8pLObOOeZQQ06Y01rq1zHTbRgsEDO5bjJngrY1lDDemTUcAjo7PfXDabr4oVt2UG8JjL2aLd7C4b6Cguh3KKagC27jQ_kzjfZM-GFJtp2Dvj7-J9uN6cDNQusOi_OhjjksIVxMZRhCCHeXvrPAYJaiyZgfEZCJLag-5F6ij=w1152-h648-no?authuser=0', 
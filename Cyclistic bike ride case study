# Portfolio https://medium.com/@ypurutcu/how-does-a-bike-share-navigate-speedy-success-c99848743d42

WITH
  combined_rides AS ( 
      #July 2020
  SELECT
    ride_id,
    rideable_type,
    CAST(started_at AS TIMESTAMP ) AS started_at,
    CAST(ended_at AS TIMESTAMP ) AS ended_at,
    start_station_name,
    CAST(start_station_id AS STRING ) AS start_station_id,
    end_station_name,
    CAST(end_station_id AS STRING ) AS end_station_id,
    start_lat,
    start_lng,
    end_lat,
    end_lng,
    member_casual,
    timestamp_diff (ended_at,started_at, minute) AS trip_duration,
    EXTRACT(DAYOFWEEK FROM started_at) AS day_of_week
  FROM
    `dataanalyst2021.cyclistic_bike_share.202007_tripdata`
  UNION ALL
    # August 2020
  SELECT
    ride_id,
    rideable_type,
    CAST(started_at AS TIMESTAMP ) AS started_at,
    CAST(ended_at AS TIMESTAMP ) AS ended_at,
    start_station_name,
    CAST(start_station_id AS STRING ) AS start_station_id,
    end_station_name,
    CAST(end_station_id AS STRING ) AS end_station_id,
    start_lat,
    start_lng,
    end_lat,
    end_lng,
    member_casual,
    timestamp_diff (ended_at,started_at, minute) AS trip_duration,
    EXTRACT(DAYOFWEEK FROM started_at) AS day_of_week
  FROM
    `dataanalyst2021.cyclistic_bike_share.202008_tripdata`
  UNION ALL
    #September 2020
  SELECT
    ride_id,
    rideable_type,
    CAST(started_at AS TIMESTAMP ) AS started_at,
    CAST(ended_at AS TIMESTAMP ) AS ended_at,
    start_station_name,
    CAST(start_station_id AS STRING ) AS start_station_id,
    end_station_name,
    CAST(end_station_id AS STRING ) AS end_station_id,
    start_lat,
    start_lng,
    end_lat,
    end_lng,
    member_casual,
   timestamp_diff (ended_at,started_at, minute) AS trip_duration,
    EXTRACT(DAYOFWEEK FROM started_at) AS day_of_week
  FROM
    `dataanalyst2021.cyclistic_bike_share.202009_tripdata`
  UNION ALL
    #October 2020
  SELECT
    ride_id,
    rideable_type,
    CAST(started_at AS TIMESTAMP ) AS started_at,
    CAST(ended_at AS TIMESTAMP ) AS ended_at,
    start_station_name,
    CAST(start_station_id AS STRING ) AS start_station_id,
    end_station_name,
    CAST(end_station_id AS STRING ) AS end_station_id,
    start_lat,
    start_lng,
    end_lat,
    end_lng,
    member_casual,
    timestamp_diff (ended_at,started_at, minute) AS trip_duration,
    EXTRACT(DAYOFWEEK FROM started_at) AS day_of_week
  FROM
    `dataanalyst2021.cyclistic_bike_share.202010_tripdata`
  UNION ALL
    # November 2020
  SELECT
    ride_id,
    rideable_type,
    CAST(started_at AS TIMESTAMP ) AS started_at,
    CAST(ended_at AS TIMESTAMP ) AS ended_at,
    start_station_name,
    CAST(start_station_id AS STRING ) AS start_station_id,
    end_station_name,
    CAST(end_station_id AS STRING ) AS end_station_id,
    start_lat,
    start_lng,
    end_lat,
    end_lng,
    member_casual,
    timestamp_diff (ended_at,started_at, minute) AS trip_duration,
    EXTRACT(DAYOFWEEK FROM started_at) AS day_of_week
 
 FROM `dataanalyst2021.cyclistic_bike_share.202011_tripdata`
  UNION ALL
    #December 2020
  SELECT
    ride_id,
    rideable_type,
    CAST(started_at AS TIMESTAMP ) AS started_at,
    CAST(ended_at AS TIMESTAMP ) AS ended_at,
    start_station_name,
    CAST(start_station_id AS STRING ) AS start_station_id,
    end_station_name,
    CAST(end_station_id AS STRING ) AS end_station_id,
    start_lat,
    start_lng,
    end_lat,
    end_lng,
    member_casual,
    timestamp_diff (ended_at,started_at, minute) AS trip_duration,
    EXTRACT(DAYOFWEEK FROM started_at) AS day_of_week
  FROM
    `dataanalyst2021.cyclistic_bike_share.202012_tripdata`
  UNION ALL
    #January 2021
  SELECT
    ride_id,
    rideable_type,
    CAST(started_at AS TIMESTAMP ) AS started_at,
    CAST(ended_at AS TIMESTAMP ) AS ended_at,
    start_station_name,
    CAST(start_station_id AS STRING ) AS start_station_id,
    end_station_name,
    CAST(end_station_id AS STRING ) AS end_station_id,
    start_lat,
    start_lng,
    end_lat,
    end_lng,
    member_casual,
    timestamp_diff (ended_at,started_at, minute) AS trip_duration,
    EXTRACT(DAYOFWEEK FROM started_at) AS day_of_week
  FROM
    `dataanalyst2021.cyclistic_bike_share.202101_tripdata`
  UNION ALL
    #February 2021
  SELECT
    ride_id,
    rideable_type,
    CAST(started_at AS TIMESTAMP ) AS started_at,
    CAST(ended_at AS TIMESTAMP ) AS ended_at,
    start_station_name,
    CAST(start_station_id AS STRING ) AS start_station_id,
    end_station_name,
    CAST(end_station_id AS STRING ) AS end_station_id,
    start_lat,
    start_lng,
    end_lat,
    end_lng,
    member_casual,
   timestamp_diff (ended_at,started_at, minute) AS trip_duration,
    EXTRACT(DAYOFWEEK FROM started_at) AS day_of_week
  FROM
    `dataanalyst2021.cyclistic_bike_share.202102_tripdata`
  UNION ALL
    #March 2021
  SELECT
    ride_id,
    rideable_type,
    CAST(started_at AS TIMESTAMP ) AS started_at,
    CAST(ended_at AS TIMESTAMP ) AS ended_at,
    start_station_name,
    CAST(start_station_id AS STRING ) AS start_station_id,
    end_station_name,
    CAST(end_station_id AS STRING ) AS end_station_id,
    start_lat,
    start_lng,
    end_lat,
    end_lng,
    member_casual,
    timestamp_diff (ended_at,started_at, minute) AS trip_duration,
    EXTRACT(DAYOFWEEK FROM started_at) AS day_of_week
  FROM
    `dataanalyst2021.cyclistic_bike_share.202103_tripdata`
  UNION ALL
    #April 2021
  SELECT
    ride_id,
    rideable_type,
    CAST(started_at AS TIMESTAMP ) AS started_at,
    CAST(ended_at AS TIMESTAMP ) AS ended_at,
    start_station_name,
    CAST(start_station_id AS STRING ) AS start_station_id,
    end_station_name,
    CAST(end_station_id AS STRING ) AS end_station_id,
    start_lat,
    start_lng,
    end_lat,
    end_lng,
    member_casual,
    timestamp_diff (ended_at,started_at, minute) AS trip_duration,
    EXTRACT(DAYOFWEEK FROM started_at) AS day_of_week
  FROM
    `dataanalyst2021.cyclistic_bike_share.202104_tripdata`
  UNION ALL
    #May 2021
  SELECT
    ride_id,
    rideable_type,
    CAST(started_at AS TIMESTAMP ) AS started_at,
    CAST(ended_at AS TIMESTAMP ) AS ended_at,
    start_station_name,
    CAST(start_station_id AS STRING ) AS start_station_id,
    end_station_name,
    CAST(end_station_id AS STRING ) AS end_station_id,
    start_lat,
    start_lng,
    end_lat,
    end_lng,
    member_casual,
    timestamp_diff (ended_at,started_at, minute) AS trip_duration,
    EXTRACT(DAYOFWEEK FROM started_at) AS day_of_week
  FROM
    `dataanalyst2021.cyclistic_bike_share.202105_tripdata`
  UNION ALL
    #June 2021
  SELECT
    ride_id,
    rideable_type,
    CAST(started_at AS TIMESTAMP ) AS started_at,
    CAST(ended_at AS TIMESTAMP ) AS ended_at,
    start_station_name,
    CAST(start_station_id AS STRING ) AS start_station_id,
    end_station_name,
    CAST(end_station_id AS STRING ) AS end_station_id,
    start_lat,
    start_lng,
    end_lat,
    end_lng,
    member_casual,
    timestamp_diff (ended_at,started_at, minute) AS trip_duration,
    EXTRACT(DAYOFWEEK FROM started_at) AS day_of_week
  FROM
    `dataanalyst2021.cyclistic_bike_share.202106_tripdata` )

SELECT * FROM combined_rides
 WHERE
    NOT( start_station_id IS NULL
      OR end_station_id IS NULL
      OR start_lat IS NULL
      OR end_lat IS NULL
      OR start_station_name LIKE '%CHECKING%'
      OR end_station_name LIKE '%CHECKING%'
      OR trip_duration < 1)

ORDER BY started_at DESC


# Temp table “combined_rides” was saved as a permanent table

ANALYSIS
#Calculate the min, max, sum,mean of ride_length   
SELECT
  rideable_type,
  member_casual,
MIN(trip_duration) AS min_trip_duration,
MAX(trip_duration) AS max_trip_duration,
SUM(trip_duration) AS sum_of_trip_duration,
ROUND (AVG(trip_duration),2)  AS average_trip_duration 
FROM  
  `dataanalyst2021.cyclistic_bike_share.combined_rides`
GROUP BY 
  rideable_type,
  member_casual
ORDER BY average_trip_duration DESC; 

#Calculate trip duration and percentages  
SELECT
  rideable_type,
  member_casual,
  COUNT(*) AS number_of_trips,
  ROUND(COUNT(*) * 100 /SUM (COUNT(*)) OVER (),2) AS percent_rides,
  SUM(trip_duration) AS sum_of_trip_duration,
  ROUND(SUM(trip_duration) * 100 /SUM (SUM(trip_duration)) OVER (),2) AS percent_trip_duration
FROM
  `dataanalyst2021.cyclistic_bike_share.combined_rides`
GROUP BY
  rideable_type,
  member_casual
ORDER BY
  percent_trip_duration DESC;

#Analysis by mode of day_of_week 
SELECT  
COUNT(*) as number_of_rides,
(SELECT CASE WHEN EXTRACT(DAYOFWEEK   FROM   started_at)=2 THEN 'Monday'
             WHEN EXTRACT(DAYOFWEEK   FROM   started_at)=3 THEN 'Tuesday' 
WHEN EXTRACT(DAYOFWEEK   FROM   started_at)=4 THEN 'Wednesday'
             WHEN EXTRACT(DAYOFWEEK   FROM   started_at)=5 THEN 'Thursday' 
WHEN EXTRACT(DAYOFWEEK   FROM   started_at)=6 THEN 'Friday'
             WHEN EXTRACT(DAYOFWEEK   FROM   started_at)=7 THEN 'Saturday'
             WHEN EXTRACT(DAYOFWEEK   FROM   started_at)=1 THEN 'Sunday' END)
  as day_of_week

FROM 
 `dataanalyst2021.cyclistic_bike_share.combined_rides`
GROUP BY day_of_week
ORDER BY
  number_of_rides DESC;

#Analysis by season (number of rides)
SELECT  
COUNT(*) as number_of_rides,
 (SELECT CASE 
    WHEN EXTRACT(MONTH  FROM   started_at)= 12 OR EXTRACT(MONTH FROM started_at)= 1 OR EXTRACT(MONTH  FROM   started_at)= 2 THEN 'Winter' 
    WHEN EXTRACT(MONTH  FROM   started_at)= 3  OR EXTRACT(MONTH FROM started_at)= 4 OR EXTRACT(MONTH  FROM   started_at)= 5 THEN 'Spring'
    WHEN EXTRACT(MONTH  FROM   started_at)= 6  OR EXTRACT(MONTH FROM started_at)= 7 OR EXTRACT(MONTH  FROM   started_at)= 8 THEN 'Summer' 
    WHEN EXTRACT(MONTH  FROM   started_at)= 9  OR EXTRACT(MONTH FROM started_at)= 10 OR EXTRACT(MONTH  FROM  started_at)= 11 THEN 'Fall'
    ELSE '-' END) as Season
FROM 
 `dataanalyst2021.cyclistic_bike_share.combined_rides`
GROUP BY Season
ORDER BY
  number_of_rides DESC;

#Analysis by season (trip duration, number of rides)
SELECT  
COUNT(*) as number_of_rides, SUM(trip_duration) as total_trip_duration_minutes, ROUND(AVG(trip_duration)) AS  mean_trip_duration_minutes, rideable_type, member_casual,
 (SELECT CASE 
    WHEN EXTRACT(MONTH  FROM   started_at)= 12 OR EXTRACT(MONTH FROM started_at)= 1 OR EXTRACT(MONTH  FROM   started_at)= 2 THEN 'Winter' 
    WHEN EXTRACT(MONTH  FROM   started_at)= 3  OR EXTRACT(MONTH FROM started_at)= 4 OR EXTRACT(MONTH  FROM   started_at)= 5 THEN 'Spring'
    WHEN EXTRACT(MONTH  FROM   started_at)= 6  OR EXTRACT(MONTH FROM started_at)= 7 OR EXTRACT(MONTH  FROM   started_at)= 8 THEN 'Summer' 
    WHEN EXTRACT(MONTH  FROM   started_at)= 9  OR EXTRACT(MONTH FROM started_at)= 10 OR EXTRACT(MONTH  FROM  started_at)= 11 THEN 'Fall'
    ELSE '-' END) as Season
FROM 
 `dataanalyst2021.cyclistic_bike_share.combined_rides`
GROUP BY Season, rideable_type, member_casual
ORDER BY
   number_of_rides DESC; 

#Analysis by time of day (Morning, Afternoon, Evening, Night)
SELECT  
member_casual,ROUND(AVG(trip_duration)) AS  mean_trip_duration_minutes,COUNT(ride_id) AS number_of_rides,
 (SELECT CASE 
    WHEN EXTRACT(TIME  FROM   started_at) BETWEEN '06:00:00' AND '11:59:59' THEN 'Morning' 
    WHEN EXTRACT(TIME  FROM   started_at) BETWEEN '12:00:00' AND '16:59:59' THEN 'Afternoon'
    WHEN EXTRACT(TIME  FROM   started_at) BETWEEN '17:00:00' AND '21:59:59' THEN 'Evening' 
    ELSE'Night' END) as time_of_day
FROM 
 `dataanalyst2021.cyclistic_bike_share.combined_rides`
GROUP BY member_casual,time_of_day
ORDER BY number_of_rides DESC

QLmonthly 								              Doc v.12.18.2024

Source:
Ellieroth, Kathrin, and Amanda Michaud. “Quits, Layoffs, and Labor Supply.” Institute Working Paper 94. Federal Reserve Bank of Minneapolis, October 2024. https://doi.org/10.21034/iwp.94. 

Description:
Monthly flow rates of workers calculated from the Current Population Survey. Harmonization procedure and exact variable definitions described in the paper above. 

Time: 
⦁	1978m1- current. The data are seasonally adjusted.

Samples:
⦁	-"all" = Working age (16+) 
⦁	Prime age = 25-54

Variable nomenclature:
⦁	time
⦁	eqall_seats = flow rate from employment to non-employment due to a quit = Number employed persons in month t who become non-employed due to quit in t+1/Number of employed persons in month t.
⦁	elall_seats = flow rate from employment to non-employment due to a layoff = Number employed persons in month t who become non-employed due to layoff in t+1/Number of employed persons in month t.
⦁	share_layoff_n_seats = enl/el
⦁	share_quit_n_seats = enq/eq

Notes:
⦁	The data are noisy month to month. We recommend taking a centered rolling average for your analysis.
⦁	Our data differ from what you might find released by BLS/FRED for several reasons. (1) Our sample size is slightly smaller because we are unable to link some cases due to data privacy scrambling. These are few. (2) We seasonally adjust the aggregate series whereas BLS has a proprietary cell seasonal adjustment algorithm. (3) BLS appear to use an iterative procedure to ensure stocks and the stocks implied by the flows line up (internal stock flow consistency). We do not do this but we have found the implied stocks are quite consistent for unemployment.
⦁	Be aware that these flows do not include "other/unknown" responses that are both missing cases and others. Missing cases include retirements because newly retired workers are not asked what happened to their last job whereas newly non-employed for other reasons are. Certainly, these flows include both layoffs and quits to non-employment. We recommend using prime age statistics for most cases but there are exceptions where one may want to use the total working age population.

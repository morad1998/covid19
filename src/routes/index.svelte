<svelte:head>
    <title>Home Page</title>
</svelte:head>

<script>
  import CovidStat from "../components/CovidStat.svelte";

  import CovidChart from "../components/CovidChart.svelte";

  import TableContainer from "../components/TableContainer.svelte";
</script>


<div class="section header">
  <div class="container">
      <h1>Covid-19</h1>
      
  </div>
</div>

<CovidStat />

<CovidChart />

<TableContainer />

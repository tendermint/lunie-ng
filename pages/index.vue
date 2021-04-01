<template>
  <div class="portfolio">
    <PortfolioBalances />
    <PortfolioDelegations />
    <PortfolioUndelegations />
  </div>
</template>

<script>
export default {
  name: `PagePortfolio`,
  middleware: 'addressRequired',
}
</script>
<style scoped>
.portfolio {
  background: var(--gray-100);
  min-height: 100vh;
}
</style>

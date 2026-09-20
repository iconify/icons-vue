<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="enx8x41-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:search-shield-20-filled" /></template>
<style>
.enx8x41-o {
  fill: currentColor;
  d: path("M9.5 3a6.5 6.5 0 0 1 5.096 10.535l3.434 3.435a.75.75 0 0 1-.976 1.133l-.084-.073l-3.435-3.434a6.47 6.47 0 0 1-3.962 1.402c.205-.447.349-.953.402-1.521a5 5 0 1 0-5.47-5.232l-.076.068c-.326.31-.815.696-1.385.936A6.5 6.5 0 0 1 9.5 3m-4.38 7.036a.574.574 0 0 1 .76 0c.509.484 1.484 1.254 2.683 1.412c.24.032.437.212.437.438v2.111c0 2.838-2.784 3.869-3.386 4.059a.37.37 0 0 1-.227 0C4.785 17.866 2 16.836 2 13.997v-2.111c0-.226.197-.406.437-.438c1.199-.158 2.174-.928 2.682-1.412");
}

</style>

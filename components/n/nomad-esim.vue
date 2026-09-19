<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="odkj3hbwk"/><path class="u67cyabqx"/><path class="kwvdjlylt"/><path class="dg5h-pbam"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:nomad-esim" /></template>
<style>
.dg5h-pbam {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  d: path("M35.76 13.363c.01-.006 4.768-3.245 7.701.727");
}

.kwvdjlylt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m29.153 17.186l6.656-3.857a1.409 1.409 0 0 1 2.114 1.225v18.897c0 1.091-2.077.759-3.02.21l-16.056-9.336v6.49l13.38 7.753c4.606 2.674 11.273.349 11.273-4.988V14.42c0-5.337-5.761-8.676-10.368-6.002l-9.538 5.533");
}

.odkj3hbwk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m18.847 30.814l-6.656 3.857a1.409 1.409 0 0 1-2.114-1.225V14.549c0-1.091 2.077-.759 3.02-.21l16.056 9.336v-6.49l-13.38-7.752C11.168 6.759 4.5 9.083 4.5 14.42v19.16c0 5.337 5.761 8.677 10.368 6.003l9.538-5.534");
}

.u67cyabqx {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  d: path("M12.24 34.637c-.01.006-4.767 3.245-7.701-.727");
}

</style>

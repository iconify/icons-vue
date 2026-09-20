<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="j_258ubty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:options-speaker-20-regular" /></template>
<style>
.j_258ubty {
  fill: currentColor;
  d: path("M12.146 10.148a.5.5 0 0 1 .853.353v6.001a.5.5 0 0 1-.854.354L10.292 15H8.5a.5.5 0 0 1-.5-.5V14H2.5a.5.5 0 0 1 0-1H8v-.5a.5.5 0 0 1 .5-.5h1.794zm3.69-.067a.5.5 0 0 1 .692.146c.614.941.971 2.066.971 3.273a6 6 0 0 1-.97 3.273a.5.5 0 0 1-.839-.546c.511-.784.809-1.72.809-2.727a4.97 4.97 0 0 0-.809-2.727a.5.5 0 0 1 .146-.692m-1.594 1.187a.5.5 0 0 1 .687.17c.363.603.571 1.309.571 2.062s-.208 1.46-.571 2.062a.5.5 0 0 1-.858-.516c.272-.451.429-.98.429-1.546s-.157-1.095-.429-1.546a.5.5 0 0 1 .171-.686M7.5 3a2.5 2.5 0 0 1 2.45 2h7.55a.5.5 0 0 1 0 1H9.95a2.501 2.501 0 0 1-4.9 0H2.5a.5.5 0 0 1 0-1h2.55A2.5 2.5 0 0 1 7.5 3m0 1a1.5 1.5 0 1 0 0 3a1.5 1.5 0 0 0 0-3");
}

</style>

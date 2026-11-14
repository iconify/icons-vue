<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xgdzedcts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:pot-drainage-hole" /></template>
<style>
.xgdzedcts {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18.75 1.75H5.25q-1.036 0-1.768.732T2.75 4.25t.732 1.768q.595.594 1.389.706l1.641 8.912q.012.064.035.125t.056.118q.033.056.075.106t.092.091q.05.042.107.075t.118.054t.125.034q.065.011.13.011h9.5q.065 0 .13-.011q.064-.012.125-.034q.062-.022.118-.054q.057-.033.107-.075t.092-.091t.075-.106t.056-.118t.035-.125l1.641-8.912q.794-.112 1.389-.706q.732-.732.732-1.768q0-2.5-2.5-2.5m-10.876 13l-1.473-8h11.198l-1.473 8zM12 9q-2.25 0-2.25 2.25T12 13.5t2.25-2.25T12 9m.53 8.72l.987.986q.696.634.731 1.579q.036.955-.628 1.644q-.663.689-1.62.689t-1.62-.689t-.628-1.644q.035-.945.731-1.579l.987-.986q.052-.053.113-.094t.13-.069t.141-.043T12 17.5t.146.014q.073.015.141.043t.13.069t.113.094");
}

</style>

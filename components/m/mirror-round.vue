<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tgykiobzz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:mirror-round" /></template>
<style>
.tgykiobzz {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m6.767 5.926l4.75-4q.05-.042.107-.075t.119-.056t.126-.034T12 1.75t.131.011t.126.034t.119.056t.107.075l4.75 4q.083.07.143.161q.418.333.811.726Q20.75 9.376 20.75 13t-2.563 6.187T12 21.75t-6.187-2.563T3.25 13t2.563-6.187q.393-.393.811-.726q.06-.091.143-.161M12 3.481l-.971.817q.476-.048.971-.048t.971.048zM7.934 8.934Q6.25 10.618 6.25 13t1.684 4.066T12 18.75t4.066-1.684T17.75 13t-1.684-4.066T12 7.25T7.934 8.934");
}

</style>

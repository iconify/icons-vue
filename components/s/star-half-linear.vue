<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k8v-t1yoe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:star-half-linear" /></template>
<style>
.k8v-t1yoe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 20.0248C11.6532 20.0248 11.3261 20.1754 10.6722 20.4765L10.6715 20.4768L10.0757 20.7512L10.0754 20.7514C7.7726 21.8116 6.62118 22.3417 5.85512 21.7602C5.08917 21.1787 5.21591 19.8708 5.46938 17.2549L5.46942 17.2544L5.53502 16.5776L5.53503 16.5775C5.60703 15.8341 5.64302 15.4624 5.53592 15.1177C5.42875 14.7731 5.19055 14.4946 4.71431 13.9376L4.71392 13.9372L4.28012 13.4299C2.60322 11.4691 1.76482 10.4886 2.05742 9.5477C2.34998 8.60693 3.57958 8.32868 6.03849 7.77223L6.03952 7.772L6.67592 7.628C7.37492 7.4699 7.72432 7.3908 8.00492 7.1778C8.2854 6.96497 8.46524 6.64241 8.82467 5.99773L8.82552 5.9962L9.15322 5.4084C10.4198 3.1361 11.0531 2 12 2");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ebgmn1bwx"/><path class="p7aq10b2c"/><path class="bt2vd8brk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:three-squares-broken" /></template>
<style>
.bt2vd8brk {
  d: path("M15 2.00439C13.7602 2.02233 13.0573 2.11429 12.5858 2.58584C12 3.17162 12 4.11443 12 6.00005V8.00005C12 9.88567 12 10.8285 12.5858 11.4143C13.1716 12 14.1144 12 16 12H18C19.8856 12 20.8284 12 21.4142 11.4143C22 10.8285 22 9.88567 22 8.00005V6.00005C22 4.11443 22 3.17162 21.4142 2.58584C20.9427 2.11429 20.2398 2.02233 19 2.00439");
}

.ebgmn1bwx {
  d: path("M7.00005 12H6.00005C4.11443 12 3.17162 12 2.58584 12.5858C2.11429 13.0573 2.02233 13.7602 2.00439 15M12 17V18C12 19.8856 12 20.8284 11.4143 21.4142C10.8285 22 9.88567 22 8.00005 22H6.00005C4.11443 22 3.17162 22 2.58584 21.4142C2.11429 20.9427 2.02233 20.2398 2.00439 19");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.p7aq10b2c {
  d: path("M12 7H11C9.11438 7 8.17157 7 7.58579 7.58579C7 8.17157 7 9.11438 7 11V13C7 14.8856 7 15.8284 7.58579 16.4142C8.17157 17 9.11438 17 11 17H13C14.8856 17 15.8284 17 16.4142 16.4142C17 15.8284 17 14.8856 17 13V12");
}

</style>

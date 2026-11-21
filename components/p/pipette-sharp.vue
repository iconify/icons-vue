<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g461-qbhh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:pipette-sharp" /></template>
<style>
.g461-qbhh {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M14.8206 14.6242L9.3758 9.1794C8.5167 8.3203 8.5167 6.9273 9.3758 6.0682C10.235 5.209 11.628 5.209 12.4871 6.0682L13.2649 6.846L16.3055 3.8054C17.3794 2.7315 19.1206 2.7315 20.1946 3.8054C21.2685 4.8794 21.2685 6.6206 20.1946 7.6945L17.154 10.7351L17.9318 11.5129C18.791 12.372 18.791 13.765 17.9318 14.6242C17.0727 15.4833 15.6797 15.4833 14.8206 14.6242ZM10.5426 10.3462L4.9092 15.9795L4.1314 19.8686L8.0205 19.0908L13.6538 13.4574M4.1314 19.8686L2.7071 21.2929");
}

</style>

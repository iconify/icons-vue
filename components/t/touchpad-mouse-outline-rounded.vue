<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ggcfvvbyv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:touchpad-mouse-outline-rounded" /></template>
<style>
.ggcfvvbyv {
  fill: currentColor;
  d: path("M18.975 18.975Q20 17.95 20 16.5V15h-7v1.5q0 1.45 1.025 2.475T16.5 20t2.475-1.025M13.025 13H15.5v-2.85q-.95.275-1.638 1.05t-.837 1.8m4.475 0h2.475q-.15-1.025-.837-1.8T17.5 10.15zm-4.9 7.4Q11 18.8 11 16.5v-3q0-2.3 1.6-3.9T16.5 8t3.9 1.6t1.6 3.9v3q0 2.3-1.6 3.9T16.5 22t-3.9-1.6M4 20q-.825 0-1.412-.587T2 18V6q0-.825.588-1.412T4 4h17q.425 0 .713.288T22 5t-.288.713T21 6H4v12h4.025q.425 0 .713.288t.287.712t-.288.713t-.712.287zm0-2V6z");
}

</style>

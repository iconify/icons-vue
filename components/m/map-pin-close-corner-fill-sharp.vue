<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x9ozstbyp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:map-pin-close-corner-fill-sharp" /></template>
<style>
.x9ozstbyp {
  fill: currentColor;
  d: path("m10.567 17.929l.423 2.928a1.001 1.001 0 0 1-1.545.975c-1.854-1.237-3.557-2.817-4.876-4.616a14 14 0 0 1-1.832-3.314A10.9 10.9 0 0 1 2 10a7.98 7.98 0 0 1 2.343-5.657A8.002 8.002 0 0 1 17.98 9.43a1 1 0 0 1-.995 1.07a6.492 6.492 0 0 0-6.418 7.429m-.44-5.932a3 3 0 1 0-.253-5.993a3 3 0 0 0 .253 5.993M17 15.586l2.293-2.293a.999.999 0 1 1 1.414 1.414L18.414 17l2.293 2.293a.999.999 0 1 1-1.414 1.414L17 18.414l-2.293 2.293a.999.999 0 1 1-1.414-1.414L15.586 17l-2.293-2.293a.999.999 0 1 1 1.414-1.414Z");
}

</style>

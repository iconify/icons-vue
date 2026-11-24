<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x67pe1bes"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:map-pin-search-corner-fill" /></template>
<style>
.x67pe1bes {
  fill: currentColor;
  d: path("m10.567 17.929l.423 2.928a1.001 1.001 0 0 1-1.545.975c-1.854-1.237-3.557-2.817-4.876-4.616a14 14 0 0 1-1.832-3.314A10.9 10.9 0 0 1 2 10a7.98 7.98 0 0 1 2.343-5.657A8.002 8.002 0 0 1 17.98 9.43a1 1 0 0 1-.995 1.07a6.492 6.492 0 0 0-6.418 7.429m-.44-5.932a3 3 0 1 0-.253-5.993a3 3 0 0 0 .253 5.993m9.194 5.91l2.386 2.386a.999.999 0 1 1-1.414 1.414l-2.386-2.386a3.83 3.83 0 1 1 1.414-1.414m-1.626-1.218a1.83 1.83 0 1 0-3.39-1.376a1.83 1.83 0 0 0 3.39 1.376");
}

</style>

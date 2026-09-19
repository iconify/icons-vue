<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ya7fz96hg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-do-not-touch" /></template>
<style>
.ya7fz96hg {
  fill: currentColor;
  d: path("m13 10.17l-2.5-2.5V1H13zM20 4h-2.5v7h-1V2H14v9.17l6 6zM9.5 3H7.01v1.18L9.5 6.67zm11.69 18.19L2.81 2.81L1.39 4.22L7 9.83v4.3l-3.32-1.9L2 13.88L9.68 22h9.54l.56.61z");
}

</style>

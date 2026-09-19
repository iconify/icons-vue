<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="vv_d4wc7o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:trade-mark" /></template>
<style>
.vv_d4wc7o {
  fill: var(--svg-color--4d5357, #4d5357);
  d: path("M2 2v7.5h10.3V34h7.5V9.5h10.3V2zm52.5 0l-6.6 13.2L41.4 2h-7.5v32h7.5V20.8L47.9 34l6.6-13.2V34H62V2z");
}

</style>

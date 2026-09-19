<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pul0nwy7p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-looks" /></template>
<style>
.pul0nwy7p {
  fill: currentColor;
  d: path("M12 6C5.93 6 1 10.93 1 17h2c0-4.96 4.04-9 9-9s9 4.04 9 9h2c0-6.07-4.93-11-11-11m0 6c2.76 0 5 2.24 5 5h2c0-3.86-3.14-7-7-7s-7 3.14-7 7h2c0-2.76 2.24-5 5-5");
}

</style>

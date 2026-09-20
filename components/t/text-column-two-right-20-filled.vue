<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="yhk6f_b4g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-column-two-right-20-filled" /></template>
<style>
.yhk6f_b4g {
  fill: currentColor;
  d: path("M17 5.75a.75.75 0 0 0-.75-.75h-2.5a.75.75 0 0 0 0 1.5h2.5a.75.75 0 0 0 .75-.75m-6 0a.75.75 0 0 0-.75-.75h-6.5a.75.75 0 0 0 0 1.5h6.5a.75.75 0 0 0 .75-.75m6 3a.75.75 0 0 0-.75-.75h-2.5a.75.75 0 0 0 0 1.5h2.5a.75.75 0 0 0 .75-.75m-6 0a.75.75 0 0 0-.75-.75h-6.5a.75.75 0 0 0 0 1.5h6.5a.75.75 0 0 0 .75-.75m6 3a.75.75 0 0 0-.75-.75h-2.5a.75.75 0 0 0 0 1.5h2.5a.75.75 0 0 0 .75-.75m-6 0a.75.75 0 0 0-.75-.75h-6.5a.75.75 0 0 0 0 1.5h6.5a.75.75 0 0 0 .75-.75m6 3a.75.75 0 0 0-.75-.75h-2.5a.75.75 0 0 0 0 1.5h2.5a.75.75 0 0 0 .75-.75m-6 0a.75.75 0 0 0-.75-.75h-6.5a.75.75 0 0 0 0 1.5h6.5a.75.75 0 0 0 .75-.75");
}

</style>

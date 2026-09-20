<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wtq9apony"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:sound-wave-circle-add-24-regular" /></template>
<style>
.wtq9apony {
  fill: currentColor;
  d: path("M17.5 12a5.5 5.5 0 1 1 0 11a5.5 5.5 0 0 1 0-11M12 2c5.523 0 10 4.477 10 10q-.002.393-.033.78a6.5 6.5 0 0 0-1.474-1.05a8.5 8.5 0 1 0-8.764 8.764c.281.54.636 1.035 1.05 1.473q-.386.032-.779.033C6.477 22 2 17.523 2 12S6.477 2 12 2m5.5 11.999a.5.5 0 0 0-.5.5V17h-2.505a.5.5 0 0 0 0 1h2.506v2.504a.5.5 0 0 0 1 0V18h2.496a.5.5 0 0 0 0-1H18v-2.501a.5.5 0 0 0-.5-.5M10.25 8a.75.75 0 0 1 .75.75v6.5a.75.75 0 0 1-1.5 0v-6.5a.75.75 0 0 1 .75-.75m-3 2a.75.75 0 0 1 .75.75v2.5a.75.75 0 0 1-1.5 0v-2.5a.75.75 0 0 1 .75-.75m6-.5a.75.75 0 0 1 .75.75v1.774a6.5 6.5 0 0 0-1.5 1.323V10.25a.75.75 0 0 1 .75-.75m3-1.5a.75.75 0 0 1 .75.75v2.27q-.782.061-1.5.295V8.75a.75.75 0 0 1 .75-.75");
}

</style>

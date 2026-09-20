<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="h-wa-1bir"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:quiz-new-28-filled" /></template>
<style>
.h-wa-1bir {
  fill: currentColor;
  d: path("M20.5 14a6.5 6.5 0 1 1 0 13a6.5 6.5 0 0 1 0-13m.75-11A3.75 3.75 0 0 1 25 6.75v7.75a7.47 7.47 0 0 0-4.5-1.5a7.49 7.49 0 0 0-5.998 2.998H6.75a.75.75 0 0 0 0 1.5h6.877a7.5 7.5 0 0 0-.608 2.503H6.75a.75.75 0 0 0 0 1.5h6.318A7.46 7.46 0 0 0 14.5 25H6.75A3.75 3.75 0 0 1 3 21.25V6.75A3.75 3.75 0 0 1 6.75 3zm-.75 13a.5.5 0 0 0-.5.5V20h-3.5a.5.5 0 0 0 0 1H20v3.5a.5.5 0 0 0 1 0V21h3.5a.5.5 0 0 0 0-1H21v-3.5a.5.5 0 0 0-.5-.5M11.502 6a.75.75 0 0 0-.692.457L8.06 12.96a.75.75 0 0 0 1.38.585l.442-1.043h3.236l.442 1.043a.75.75 0 0 0 1.38-.584l-2.748-6.503a.75.75 0 0 0-.69-.458m6.248 0a.75.75 0 0 0-.75.75V8h-1.248a.75.75 0 0 0 0 1.5H17v1.248a.75.75 0 0 0 1.5 0V9.5h1.25a.75.75 0 0 0 0-1.5H18.5V6.75a.75.75 0 0 0-.75-.75m-5.266 5.002h-1.967l.984-2.327z");
}

</style>

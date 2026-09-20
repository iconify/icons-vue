<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="a5mddnbua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:omega-16-filled" /></template>
<style>
.a5mddnbua {
  fill: currentColor;
  d: path("M8 1a7 7 0 0 1 7 7c0 1.743-.776 3.195-1.592 4.243c-.39.502-.8.924-1.16 1.257h2.002a.75.75 0 0 1 0 1.5h-3.178a1.075 1.075 0 0 1-1.07-.965l-.004-.11l.008-.133c.038-.306.204-.575.444-.749c.658-.504 1.264-1.064 1.775-1.72c.7-.9 1.275-2.035 1.275-3.323a5.5 5.5 0 1 0-11 0c0 1.288.575 2.422 1.275 3.322a9.2 9.2 0 0 0 1.775 1.721c.274.199.452.521.452.882c0 .593-.48 1.075-1.074 1.075H1.75a.75.75 0 0 1 0-1.5h2.002a10.5 10.5 0 0 1-1.16-1.257C1.776 11.195 1 9.743 1 8a7 7 0 0 1 7-7");
}

</style>

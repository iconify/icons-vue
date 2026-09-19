<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v84x7gbgr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-bathroom" /></template>
<style>
.v84x7gbgr {
  fill: currentColor;
  d: path("M8 14c0-.55.45-1 1-1s1 .45 1 1s-.45 1-1 1s-1-.45-1-1m4 1c.55 0 1-.45 1-1s-.45-1-1-1s-1 .45-1 1s.45 1 1 1m3 0c.55 0 1-.45 1-1s-.45-1-1-1s-1 .45-1 1s.45 1 1 1m-3-7.5c-1.76 0-3.22 1.31-3.46 3h6.93a3.52 3.52 0 0 0-3.47-3M12 6c2.76 0 5 2.24 5 5v1H7v-1c0-2.76 2.24-5 5-5M9 18c.55 0 1-.45 1-1s-.45-1-1-1s-1 .45-1 1s.45 1 1 1m3 0c.55 0 1-.45 1-1s-.45-1-1-1s-1 .45-1 1s.45 1 1 1m3 0c.55 0 1-.45 1-1s-.45-1-1-1s-1 .45-1 1s.45 1 1 1m5-14H4v16h16zm0-2c1.1 0 2 .9 2 2v16c0 1.1-.9 2-2 2H4c-1.1 0-2-.9-2-2V4c0-1.1.9-2 2-2z");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="nbu3agi5o"/><circle class="dbvavxbgu"/><circle class="un3qsz6gz"/><path class="er46b6b3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:nextclouddev" /></template>
<style>
.dbvavxbgu {
  cx: 9.53px;
  cy: 19.69px;
  r: 5.03px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.er46b6b3z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.59 37.75v-8h1.3a4 4 0 0 1 0 8Zm10.921-1a1.94 1.94 0 0 1-1.7 1a2.006 2.006 0 0 1-2-2v-1.3a2 2 0 0 1 4 0v.7h-4m5.599-2.7l2 5.3l2-5.3");
}

.nbu3agi5o {
  cx: 24px;
  cy: 19.69px;
  r: 9.44px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.un3qsz6gz {
  cx: 38.47px;
  cy: 19.69px;
  r: 5.03px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

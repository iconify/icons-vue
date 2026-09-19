<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t5v_n6_hn"/><path class="q-udmo56r"/><path class="cz59495ro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-dining" /></template>
<style>
.cz59495ro {
  fill: currentColor;
  d: path("M8 12.23V19h1.5v-6.77c.86-.22 1.5-1 1.5-1.93V6.5c0-.28-.22-.5-.5-.5c-.27 0-.5.22-.5.5V9h-.75V6.5c0-.28-.22-.5-.5-.5s-.5.22-.5.5V9H7.5V6.5c0-.28-.22-.5-.5-.5s-.5.22-.5.5v3.8c0 .93.64 1.71 1.5 1.93m5.92.35l.08.04V19h1.5v-6.38l.08-.03c.97-.47 1.67-1.7 1.67-3.18c0-1.88-1.12-3.41-2.5-3.41c-1.37 0-2.5 1.52-2.5 3.4c0 1.48.7 2.71 1.67 3.18");
}

.q-udmo56r {
  fill: currentColor;
  d: path("M20 2H4c-1.1 0-2 .9-2 2v16c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2V4c0-1.1-.9-2-2-2m0 18H4V4h16z");
}

.t5v_n6_hn {
  fill: currentColor;
  d: path("M4 20h16V4H4zM14.75 6c1.38 0 2.5 1.53 2.5 3.41c0 1.48-.7 2.71-1.67 3.18l-.08.03V19H14v-6.38l-.08-.04c-.97-.47-1.67-1.7-1.67-3.18c0-1.88 1.13-3.4 2.5-3.4m-8.25.5c0-.28.22-.5.5-.5s.5.22.5.5V9h.75V6.5c0-.28.22-.5.5-.5s.5.22.5.5V9H10V6.5c0-.28.23-.5.5-.5c.28 0 .5.22.5.5v3.8c0 .93-.64 1.71-1.5 1.93V19H8v-6.77c-.86-.22-1.5-1-1.5-1.93z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xhzl3v4bc"/><circle class="jie5odout"/><path class="txlj_jnuj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-manage-accounts" /></template>
<style>
.jie5odout {
  cx: 10px;
  cy: 8px;
  r: 4px;
  fill: currentColor;
}

.txlj_jnuj {
  fill: currentColor;
  d: path("M20.75 16c0-.22-.03-.42-.06-.63l.84-.73c.18-.16.22-.42.1-.63l-.59-1.02a.49.49 0 0 0-.59-.22l-1.06.36q-.48-.405-1.08-.63l-.22-1.09a.5.5 0 0 0-.49-.4h-1.18c-.24 0-.44.17-.49.4l-.22 1.09q-.6.225-1.08.63l-1.06-.36a.496.496 0 0 0-.59.22l-.59 1.02c-.12.21-.08.47.1.63l.84.73c-.03.21-.06.41-.06.63s.03.42.06.63l-.84.73c-.18.16-.22.42-.1.63l.59 1.02c.12.21.37.3.59.22l1.06-.36q.48.405 1.08.63l.22 1.09c.05.23.25.4.49.4h1.18c.24 0 .44-.17.49-.4l.22-1.09q.6-.225 1.08-.63l1.06.36c.23.08.47-.02.59-.22l.59-1.02c.12-.21.08-.47-.1-.63l-.84-.73c.03-.21.06-.41.06-.63M17 18c-1.1 0-2-.9-2-2s.9-2 2-2s2 .9 2 2s-.9 2-2 2");
}

.xhzl3v4bc {
  fill: currentColor;
  d: path("M10.67 13.02c-.22-.01-.44-.02-.67-.02c-2.42 0-4.68.67-6.61 1.82c-.88.52-1.39 1.5-1.39 2.53V19c0 .55.45 1 1 1h8.26a6.96 6.96 0 0 1-.59-6.98");
}

</style>

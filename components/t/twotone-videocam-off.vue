<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o090dcc3u"/><path class="ys1_-66vh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-videocam-off" /></template>
<style>
.o090dcc3u {
  fill: currentColor;
  d: path("M12.39 8L15 10.61V8zM5 8v8h9.73l-8-8z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.ys1_-66vh {
  fill: currentColor;
  d: path("M3.41 1.86L2 3.27L4.73 6H4c-.55 0-1 .45-1 1v10c0 .55.45 1 1 1h12c.21 0 .39-.08.55-.18L19.73 21l1.41-1.41zM5 16V8h1.73l8 8zm10-8v2.61l6 6V6.5l-4 4V7c0-.55-.45-1-1-1h-5.61l2 2z");
}

</style>

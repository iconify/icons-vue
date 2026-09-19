<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zbfscyo4e"/><path class="hu2wp5a9w"/><path class="ho-y2ebnw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-flip-camera-ios" /></template>
<style>
.ho-y2ebnw {
  fill: currentColor;
  d: path("M12 17c-2.21 0-4-1.79-4-4h2l-2.5-2.5l-.01.01L5 13h2c0 2.76 2.24 5 5 5c.86 0 1.65-.24 2.36-.62l-.74-.74c-.49.23-1.04.36-1.62.36m0-9c-.86 0-1.65.24-2.36.62l.74.73C10.87 9.13 11.42 9 12 9c2.21 0 4 1.79 4 4h-2l2.5 2.5l.01-.01L19 13h-2c0-2.76-2.24-5-5-5");
}

.hu2wp5a9w {
  fill: currentColor;
  d: path("M20 5h-3.17L15 3H9L7.17 5H4c-1.1 0-2 .9-2 2v12c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2V7c0-1.1-.9-2-2-2m0 14H4V7h4.05l1.83-2h4.24l1.83 2H20z");
}

.zbfscyo4e {
  fill: currentColor;
  d: path("M14.12 5H9.88L8.05 7H4v12h16V7h-4.05zM12 18c-2.76 0-5-2.24-5-5H5l2.49-2.49l.01-.01L10 13H8c0 2.21 1.79 4 4 4c.58 0 1.13-.13 1.62-.35l.74.74c-.71.37-1.5.61-2.36.61m7-5l-2.49 2.49l-.01.01L14 13h2c0-2.21-1.79-4-4-4c-.58 0-1.13.13-1.62.35l-.74-.73C10.35 8.24 11.14 8 12 8c2.76 0 5 2.24 5 5z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>

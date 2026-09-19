<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="o-ea71vus"/><circle class="urvtz7e9f"/><circle class="fbn8-kl8v"/><path class="ixvy8xhwz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:smiling-face-with-open-mouth" /></template>
<style>
.fbn8-kl8v {
  cx: 43.5px;
  cy: 24.5px;
  r: 5px;
  fill: currentColor;
}

.ixvy8xhwz {
  fill: currentColor;
  d: path("M47.179 35.983C43.715 35.321 38.597 34.64 32 34.64h-.001c-6.595 0-11.714.681-15.177 1.343C15.473 36.242 15 37.247 15 38.05c0 7.271 5.611 14.591 16.999 14.591H32c11.389 0 17.001-7.319 17.001-14.591c0-.803-.474-1.808-1.822-2.067m-1.204 3.787c-.054.442-.138.976-.265 1.553c-.143.64-.262.936-1.266.816c-1.921-.229-22.968-.229-24.888 0c-1.004.119-1.124-.177-1.266-.816a16 16 0 0 1-.265-1.553c-.09-.743-.011-1.269 1.283-1.486c2.195-.368 6.838-1.013 12.69-1.013c5.854 0 10.496.645 12.691 1.013c1.296.217 1.375.742 1.286 1.486");
}

.o-ea71vus {
  fill: currentColor;
  d: path("M32 2C15.432 2 2 15.432 2 32s13.432 30 30 30s30-13.432 30-30S48.568 2 32 2m0 57.5C16.836 59.5 4.5 47.164 4.5 32S16.836 4.5 32 4.5S59.5 16.836 59.5 32S47.164 59.5 32 59.5");
}

.urvtz7e9f {
  cx: 20.5px;
  cy: 24.5px;
  r: 5px;
  fill: currentColor;
}

</style>

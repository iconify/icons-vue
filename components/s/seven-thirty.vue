<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="w2mgx8b7t"/><path class="p8ytygbcx"/><path class="hb12r_ckv"/><path class="w_qan80ov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:seven-thirty" /></template>
<style>
.hb12r_ckv {
  fill: var(--svg-color--85939c, #85939c);
  d: path("M30.02 52.784c0 1.433.845 2.593 1.884 2.593c1.04 0 1.885-1.16 1.885-2.593v-21.01c0-1.437-.846-2.597-1.885-2.597s-1.884 1.16-1.884 2.597z");
}

.p8ytygbcx {
  fill: var(--svg-color--98a9b4, #98a9b4);
  d: path("M0 31.895c0 17.583 14.306 31.889 31.891 31.889s31.893-14.306 31.893-31.889C63.784 14.306 49.477 0 31.891 0S0 14.306 0 31.895m6.209 0c0-14.164 11.522-25.686 25.682-25.686c14.164 0 25.684 11.522 25.684 25.686c0 14.162-11.521 25.682-25.684 25.682c-14.16 0-25.682-11.52-25.682-25.682");
}

.w_qan80ov {
  fill: var(--svg-color--788288, #788288);
  d: path("M21.751 43.65c-.741 1.226-.616 2.656.272 3.19c.892.538 2.215-.022 2.954-1.251l7.854-13.02c.737-1.229.612-2.661-.278-3.193c-.888-.537-2.213.022-2.952 1.246l-7.85 13.03");
}

.w2mgx8b7t {
  cx: 31.893px;
  cy: 31.891px;
  r: 29.544px;
  fill: var(--svg-color--e0e7ec, #e0e7ec);
}

</style>

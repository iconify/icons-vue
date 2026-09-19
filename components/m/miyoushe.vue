<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="g2wj9jbhp"/><g class="y9tr6bcfx"><path class="w66c-lteq"/><path class="hczu301nk"/></g><g class="y9tr6bcfx"><path class="lvpicyb-s"/><path class="nlp198bwx"/></g><g class="y9tr6bcfx"><path class="lepkm3bpi"/><path class="k_s1pmbbv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:miyoushe" /></template>
<style>
.g2wj9jbhp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 5.5h29c2.216 0 4 1.784 4 4v29c0 2.216-1.784 4-4 4h-29c-2.216 0-4-1.784-4-4v-29c0-2.216 1.784-4 4-4");
}

.hczu301nk {
  d: path("M16.443 42.478c-1.72-6.016-1.98-8.545.504-11.146c5.436-5.694 12.51-6.933 16.149-7.249c3.288-.285 4.5.495 6.223 3.65c1.09 1.997 2.138 3.74 3.181 5.454");
}

.k_s1pmbbv {
  d: path("M30.586 15.694c.056 2.44.173 3.84.597 6.07");
}

.lepkm3bpi {
  d: path("m33.208 21.095l-2.912.96c-1.668.551-2.14.152-2.393-.904c-.547-2.29-.766-6.558-.23-9.563c.238-1.338.993-1.931 1.854-2.446c.784-.468 1.531-.7 2.296-.951c1.043-.342 1.723.207 1.652 1.48c-.172 3.097-.09 5.58.305 8.662c.206 1.611.312 2.47-.572 2.762");
}

.lvpicyb-s {
  d: path("m18.036 26.563l-2.912 2.126c-1.531 1.119-1.968-.07-2.22-.782c-.748-2.106-.84-6.786-.343-9.883c.158-.986.934-1.893 1.794-2.399c.843-.496 1.531-.763 2.297-1.143c1.043-.518 1.58.207 1.511 1.057c-.233 2.904-.117 5.758.277 8.615c.217 1.573.408 1.816-.404 2.41");
}

.nlp198bwx {
  d: path("M15.495 21.726c-.05 2.03.067 4.234.641 6.226");
}

.w66c-lteq {
  d: path("M21.813 35.108c.297 1.16.679 1.895 1.018 2.54m9.271-7.248c.339.78.628 1.737 1.11 2.501");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="v006a0whm"/><circle class="t_9en2b6w"/><path class="jbgsltp3a"/><rect class="yuvw6qb-o"/><path class="a1xiefbbk"/><path class="ll0g54h-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:miles-and-more" /></template>
<style>
.a1xiefbbk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.511 33.735c0-.926.75-1.676 1.676-1.676h0m-1.676 0V36.5m6.038-.846a1.68 1.68 0 0 1-1.457.846h0c-.925 0-1.676-.75-1.676-1.676v-1.09c0-.925.75-1.675 1.676-1.675h0c.926 0 1.676.75 1.676 1.676v.545h-3.351M15.244 36.5h-.567c-.375 0-.727-.18-.948-.483l-2.325-3.196c-.3-.392-.825-.909-.825-1.674c0-.722.587-1.35 1.403-1.35c.795 0 1.359.628 1.359 1.35c0 .765-.62 1.42-1.766 1.636c-1.277.243-2.075.943-2.075 2.098c0 .934.589 1.619 1.766 1.619c1.547 0 2.457-1.467 3.802-3.27");
}

.jbgsltp3a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.012 23.699v4.441m9.268-.374c.307.257.637.375 1.379.375h.376a1.11 1.11 0 0 0 1.108-1.11h0a1.11 1.11 0 0 0-1.108-1.111h-.752a1.11 1.11 0 0 1-1.108-1.11h0c0-.614.496-1.11 1.108-1.11h.376c.742 0 1.072.117 1.378.374m-4.695 3.221a1.68 1.68 0 0 1-1.456.845h0c-.926 0-1.676-.75-1.676-1.675v-1.09c0-.925.75-1.676 1.676-1.676h0c.925 0 1.676.75 1.676 1.676v.545H22.21m-2.388-4.483v5.866c0 .462.375.838.837.838h.252m-2.899 8.352v-6.696l3.352 6.703l3.352-6.693V36.5");
}

.ll0g54h-q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29c-2.2 0-4 1.8-4 4v29c0 2.2 1.8 4 4 4h29c2.2 0 4-1.8 4-4v-29c0-2.2-1.8-4-4-4");
}

.t_9en2b6w {
  cx: 18.012px;
  cy: 21.646px;
  r: 0.75px;
  fill: currentColor;
}

.v006a0whm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 28.133v-6.696l3.352 6.703l3.351-6.693v6.693");
}

.yuvw6qb-o {
  width: 3.352px;
  height: 4.441px;
  x: 26.415px;
  y: 32.059px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.676px;
  ry: 1.676px;
}

</style>

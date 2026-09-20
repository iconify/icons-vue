<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><ellipse transform="rotate(-11.445 7.946 21.447)" class="hoq_m6luz"/><ellipse class="obh0p2bta"/><ellipse class="p3beux3si"/><ellipse transform="rotate(-78.555 40.054 21.447)" class="viinksbnx"/><path class="r4395-b-k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:meowstodon" /></template>
<style>
.hoq_m6luz {
  cx: 7.946px;
  cy: 21.447px;
  rx: 4.363px;
  ry: 6.122px;
}

.obh0p2bta {
  cx: 17.889px;
  cy: 13.133px;
  rx: 4.857px;
  ry: 6.761px;
}

.p3beux3si {
  cx: 29.966px;
  cy: 13.133px;
  rx: 4.857px;
  ry: 6.761px;
}

.r4395-b-k {
  d: path("M38.123 35.684c0-2.097-1.085-3.94-2.75-5.014c-2.58-1.713-3.136-2.046-5.002-4.73a8.09 8.09 0 0 0-6.558-3.36c-2.598.004-5.037 1.362-6.52 3.306c-1.852 2.664-2.433 3.112-4.986 4.809c-1.529 1.075-2.713 2.976-2.713 4.989a5.937 5.937 0 0 0 5.933 5.941c4.068.077 5.407-1.55 7.935-1.651c3.013-.122 5.487 1.71 8.556 1.647c3.449.004 6.105-2.656 6.105-5.937");
}

.viinksbnx {
  cx: 40.054px;
  cy: 21.447px;
  rx: 6.122px;
  ry: 4.363px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

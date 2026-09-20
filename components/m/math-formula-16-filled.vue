<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="wlpnpq8or"/><path class="qr1crmbzg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:math-formula-16-filled" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.qr1crmbzg {
  d: path("M9.636 7.665a1.5 1.5 0 0 0-2.338-.274l-.328.328a.75.75 0 0 0 1.06 1.06l.329-.328l1.192 1.937L7.22 12.72a.75.75 0 0 0 1.06 1.06l2.079-2.078l1.005 1.633a1.5 1.5 0 0 0 2.338.274l.328-.328a.75.75 0 0 0-1.06-1.06l-.329.328l-1.192-1.937L13.78 8.28a.75.75 0 0 0-1.06-1.06l-2.08 2.077z");
}

.wlpnpq8or {
  d: path("M8.753 1.502C7.07.24 4.659 1.347 4.519 3.445L4.449 4.5H3.75a.75.75 0 0 0 0 1.5h.598l-.42 6.293a1.25 1.25 0 0 1-1.674 1.092l-.247-.09a.75.75 0 0 0-.513 1.41l.248.09a2.75 2.75 0 0 0 3.683-2.402L5.852 6H7.25a.75.75 0 1 0 0-1.5H5.952l.063-.955a1.15 1.15 0 0 1 1.838-.843l.197.148a.75.75 0 1 0 .9-1.2z");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":232};
const content = `<path class="pvdy5m6ci"/><path class="p613yzxyc"/><path class="fvmiir3gg"/><path class="n30mwp9ht"/><path class="xqcun-b4t"/><path class="vfjjajbkh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:sketch" /></template>
<style>
.fvmiir3gg {
  fill: var(--svg-color--fdad00, #fdad00);
  d: path("M51.846 82.608L128 231.662l76.154-149.054z");
}

.n30mwp9ht {
  fill: var(--svg-color--fdd231, #fdd231);
  d: path("m55.855 7.628l-4.009 74.979L128 0zm148.298 74.98l-4.008-74.98L128 .001z");
}

.p613yzxyc {
  fill: var(--svg-color--eb6c00, #eb6c00);
  d: path("m0 82.608l128 149.054L51.846 82.608zm204.153 0L128 231.662L255.999 82.608z");
}

.pvdy5m6ci {
  fill: var(--svg-color--fdb300, #fdb300);
  d: path("M128 0L55.855 7.628L0 82.607l128 149.055L256 82.607L200.146 7.628z");
}

.vfjjajbkh {
  fill: var(--svg-color--feeeb7, #feeeb7);
  d: path("M128 0L51.846 82.607h152.308z");
}

.xqcun-b4t {
  fill: var(--svg-color--fdad00, #fdad00);
  d: path("M204.154 82.608h51.845l-55.854-74.98zM0 82.608h51.846l4.009-74.98z");
}

</style>

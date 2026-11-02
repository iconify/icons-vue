<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ovo-jbc3z"/><path class="jn5ywxpeu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:shopping-cart-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.jn5ywxpeu {
  d: path("M5.917 5.598L6.618 7H19c.397 0 .779.127 1.1.36c.885.641 1.123 1.869.87 2.883l-1 4c-.178.713-.52 1.382-1.043 1.905c-.511.511-1.195.852-1.927.852h-7c-.699 0-1.336-.358-1.82-.842c-.506-.506-.866-1.14-1.116-1.807L4.083 6.402c-.212-.416-.459-.823-.79-1.155c-.093-.093-.2-.198-.325-.248A.999.999 0 0 1 3 3c.698 0 1.336.358 1.82.842c.493.493.848 1.108 1.097 1.756m3.019 8.051c.15.399.354.791.658 1.095c.085.084.275.256.406.256h7c.201 0 .377-.13.513-.266c.266-.266.427-.616.517-.977l1-4c.055-.218.065-.567-.083-.757H7.193Zm-1.778 5.572a2 2 0 1 1 3.684 1.558a2 2 0 0 1-3.684-1.558m9 0a2 2 0 1 1 3.684 1.558a2 2 0 0 1-3.684-1.558");
}

.ovo-jbc3z {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4.814 8.351A1 1 0 0 1 5.75 7H19c.397 0 .779.127 1.1.36c.885.641 1.123 1.869.87 2.883l-1 4c-.178.713-.52 1.382-1.043 1.905c-.511.511-1.195.852-1.927.852h-7c-.699 0-1.336-.358-1.82-.842c-.506-.506-.866-1.14-1.116-1.807Z");
}

</style>

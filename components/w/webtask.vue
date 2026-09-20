<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="n76m2zb4y"/><path class="k49ouhg8u"/><path class="zgn2ekb0u"/><path class="i-rkqyfpm"/><path class="kzili8zwg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:webtask" /></template>
<style>
.i-rkqyfpm {
  fill: var(--svg-color--f9e862, #F9E862);
  d: path("M204.8 204.8H102.4V102.4h102.4z");
}

.k49ouhg8u {
  fill: var(--svg-color--e56e62, #E56E62);
  d: path("M256 256H51.2V51.2H256z");
}

.kzili8zwg {
  fill: var(--svg-color--fff, #FFF);
  d: path("M153.6 153.6h-51.2v-51.2h51.2z");
}

.n76m2zb4y {
  fill: var(--svg-color--5f3237, #5F3237);
  d: path("M256 256H0V0h256z");
}

.zgn2ekb0u {
  fill: var(--svg-color--ed955b, #ED955B);
  d: path("M204.8 204.8H51.2V51.2h153.6z");
}

</style>

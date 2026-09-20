<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qrogcpsaq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:signal-cellular-alt-rounded" /></template>
<style>
.qrogcpsaq {
  fill: currentColor;
  d: path("M6.236 18.765Q6 18.529 6 18.192v-2.384q0-.337.236-.572Q6.47 15 6.808 15t.572.236q.236.235.236.572v2.384q0 .337-.236.573T6.808 19t-.572-.236m5.807 0q-.235-.235-.235-.572v-7.384q0-.337.235-.572q.236-.236.573-.236t.572.236t.235.572v7.384q0 .337-.236.573q-.235.235-.571.235q-.337 0-.573-.236m5.577 0q-.235-.235-.235-.572V5.808q0-.337.235-.572q.236-.236.572-.236t.573.236q.235.235.235.572v12.384q0 .337-.236.573q-.235.235-.572.235t-.572-.236");
}

</style>

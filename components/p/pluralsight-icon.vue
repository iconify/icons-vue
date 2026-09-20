<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<defs><linearGradient id="SVGoNoExboy" x1="49.999%" x2="49.999%" y1="1.576%" y2="100.443%"><stop offset="0%" class="yqalt7-ym"/><stop offset="100%" class="w4d5g3ckk"/></linearGradient></defs><path fill="url(#SVGoNoExboy)" class="kzogplbby"/><path class="wy8ga_86o"/><path class="p70v_dbdp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:pluralsight-icon" /></template>
<style>
.kzogplbby {
  d: path("M256 128c0 70.695-57.31 128-128.003 128C57.303 256 0 198.695 0 128S57.303 0 127.997 0C198.69 0 256 57.305 256 128");
}

.p70v_dbdp {
  fill: var(--svg-color--fffffe, #fffffe);
  d: path("M68.609 76.002v103.983l90.046-51.995zm11.029 19.103l56.966 32.885l-56.966 32.898z");
}

.w4d5g3ckk {
  stop-color: var(--svg-color--d7197e, #d7197e);
}

.wy8ga_86o {
  fill: var(--svg-color--fffffe, #fffffe);
  d: path("M95.092 61.479v133.029l115.207-66.511zm11.029 19.103l82.12 47.415l-82.12 47.414z");
}

.yqalt7-ym {
  stop-color: var(--svg-color--df5430, #df5430);
}

</style>

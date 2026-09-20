<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n3djo7f3c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:more-outline-rounded" /></template>
<style>
.n3djo7f3c {
  fill: currentColor;
  d: path("M9.173 19q-.379 0-.727-.164q-.348-.165-.565-.463l-4.135-5.385q-.342-.447-.342-.988t.342-.988l4.135-5.385q.217-.298.565-.462T9.173 5h10.212q.67 0 1.143.472q.472.472.472 1.144v10.769q0 .67-.472 1.143q-.472.472-1.143.472zm0-1h10.212q.269 0 .442-.173t.173-.442V6.615q0-.269-.173-.442T19.385 6H9.173q-.154 0-.279.058t-.221.173l-4.134 5.385q-.135.173-.135.384t.134.385l4.135 5.384q.096.116.221.173t.279.058m1.251-5.46q.23-.23.23-.54t-.23-.54t-.54-.23t-.539.23t-.23.54t.23.54t.54.23t.539-.23m3.5 0q.23-.23.23-.54t-.23-.54t-.54-.23q-.309 0-.539.23t-.23.54t.23.54t.54.23t.539-.23m3.5 0q.23-.23.23-.54t-.23-.54t-.54-.23t-.539.23t-.23.54t.23.54t.54.23t.539-.23M12.192 12");
}

</style>

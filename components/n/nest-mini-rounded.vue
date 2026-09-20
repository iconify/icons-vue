<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g96na8bed"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:nest-mini-rounded" /></template>
<style>
.g96na8bed {
  fill: currentColor;
  d: path("M8.04 13.54q.23-.23.23-.54t-.23-.54t-.54-.23t-.54.23t-.23.54t.23.54t.54.23t.54-.23m2.46.23q.31 0 .54-.23t.23-.54t-.23-.54t-.54-.23t-.54.23t-.23.54t.23.54t.54.23m3 0q.31 0 .54-.23t.23-.54t-.23-.54t-.54-.23t-.54.23t-.23.54t.23.54t.54.23m3.54-.23q.23-.23.23-.54t-.23-.54t-.54-.23t-.54.23t-.23.54t.23.54t.54.23t.54-.23m-8.456 7.536q-1.6-.693-2.783-1.877q-1.184-1.184-1.877-2.783T3.231 13q0-3.508 2.384-6.051T11.5 4.223V1q0-.213.143-.357T12 .5t.357.143T12.5 1v3.223q3.502.183 5.886 2.726Q20.769 9.492 20.769 13q0 1.817-.693 3.416q-.693 1.6-1.877 2.783q-1.184 1.184-2.783 1.877T12 21.769t-3.416-.693");
}

</style>

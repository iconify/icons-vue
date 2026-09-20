<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c8jzk6cwk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mobile-menu-outline" /></template>
<style>
.c8jzk6cwk {
  fill: currentColor;
  d: path("M8 21.789q-.31 0-.54-.23t-.23-.54t.23-.54t.54-.229t.54.23t.23.54t-.23.539t-.54.23m3.46-.23q-.23-.23-.23-.54t.23-.54q.23-.229.54-.229t.54.23t.23.54t-.23.539t-.54.23t-.54-.23m4 0q-.23-.23-.23-.54t.23-.54q.23-.229.54-.229t.54.23t.23.54t-.23.539t-.54.23t-.54-.23m.732-5.175V3.616q0-.27-.173-.443T15.577 3H8.423q-.27 0-.442.173q-.173.173-.173.443v12.769q0 .269.173.442t.442.173h7.154q.27 0 .442-.173q.173-.173.173-.443M12.588 6.089q.22-.22.22-.55q0-.329-.22-.549t-.55-.22t-.548.22t-.22.55t.22.549t.549.22t.549-.22m-4.78 10.296V17V3zm9.384-12.769v2.127q.31-.002.52.24t.211.55v1.281q0 .31-.21.551q-.211.242-.52.24v7.78q0 .672-.473 1.144q-.472.472-1.143.472H8.423q-.671 0-1.143-.472t-.472-1.144V3.616q0-.672.472-1.144T8.423 2h7.154q.671 0 1.143.472t.472 1.144");
}

</style>

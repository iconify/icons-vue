<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pzvy7f4cc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mobile-2-outline" /></template>
<style>
.pzvy7f4cc {
  fill: currentColor;
  d: path("M7.616 22q-.672 0-1.144-.472T6 20.385V3.615q0-.69.463-1.152T7.616 2h8.846q.67 0 1.143.472q.472.472.472 1.144V6.83q.373.04.648.31q.275.269.275.648v1.769q0 .379-.275.648t-.648.31v9.869q0 .67-.472 1.143q-.472.472-1.143.472zm0-1h8.846q.269 0 .442-.173t.173-.442V3.615q0-.269-.173-.442T16.462 3H7.616q-.27 0-.443.173T7 3.616v16.769q0 .269.173.442t.443.173M7 21V3zm5.588-1.99q.22-.22.22-.549q0-.328-.22-.548t-.55-.22t-.548.22t-.22.549t.22.549t.549.22t.549-.22");
}

</style>

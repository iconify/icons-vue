<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wb0aqbcxs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mobile-screensaver" /></template>
<style>
.wb0aqbcxs {
  fill: currentColor;
  d: path("M7.616 22q-.672 0-1.144-.472T6 20.385V3.615q0-.69.463-1.152T7.616 2h8.846q.67 0 1.143.472q.472.472.472 1.144V6.83q.373.04.648.31q.275.269.275.648v1.769q0 .379-.275.648t-.648.31v9.869q0 .67-.472 1.143q-.472.472-1.143.472zm.884-7.23h7.077l-2.144-2.886l-1.894 2.5l-1.395-1.844zm6.857-4.836q.22-.22.22-.55q0-.328-.22-.549q-.22-.22-.55-.22q-.328 0-.548.22t-.22.55t.22.549t.549.22t.549-.22");
}

</style>

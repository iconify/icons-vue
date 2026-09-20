<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sos-zmjgz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mobile-code" /></template>
<style>
.sos-zmjgz {
  fill: currentColor;
  d: path("M7.616 22q-.672 0-1.144-.472T6 20.385V3.615q0-.69.463-1.152T7.616 2h8.846q.67 0 1.143.472q.472.472.472 1.144V6.83q.373.04.648.31q.275.269.275.648v1.769q0 .379-.275.648t-.648.31v2.618h-2.635q-2.23 0-3.798 1.568q-1.567 1.567-1.567 3.798V22zm11.496-.611l-.689-.714l2.175-2.175l-2.175-2.175l.689-.713L22 18.5zm-3.762 0L12.462 18.5l2.888-2.888l.688.713l-2.175 2.175l2.175 2.175zM12.588 6.088q.22-.22.22-.55q0-.329-.22-.549t-.55-.22t-.548.22t-.22.55t.22.549t.549.22t.549-.22");
}

</style>

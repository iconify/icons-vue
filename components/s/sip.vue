<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o_xq3eooy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:sip" /></template>
<style>
.o_xq3eooy {
  fill: currentColor;
  d: path("M11.5 14.692h1V9.308h-1zm2.808 0h.884v-2h2.731q.327 0 .548-.22q.221-.222.221-.549v-1.846q0-.327-.22-.548q-.222-.221-.549-.221h-3.615zm-9 0h3.615q.327 0 .548-.22q.221-.222.221-.549v-1.596q0-.327-.22-.548q-.222-.221-.549-.221h-2.73v-1.366h3.5v-.884H6.076q-.327 0-.548.22q-.221.222-.221.549v1.596q0 .327.22.548q.222.221.549.221h2.73v1.366h-3.5zm9.884-2.884v-1.616h2.616v1.616zM4.616 19q-.691 0-1.153-.462T3 17.384V6.616q0-.691.463-1.153T4.615 5h14.77q.69 0 1.152.463T21 6.616v10.769q0 .69-.463 1.153T19.385 19z");
}

</style>

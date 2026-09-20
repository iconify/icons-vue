<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sv_sybbvp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:youtube-activity-2" /></template>
<style>
.sv_sybbvp {
  fill: currentColor;
  d: path("M19.154 19.5v-2h-2v-1h2v-2h1v2h2v1h-2v2zm-9.058-4.942L14.604 12l-4.508-2.539zM12 6.019l.933.003q.933.003 2.149.04t2.417.106t1.763.218q.476.137.846.492t.505.841q.262.927.324 2.207t.038 2.287q-.296-.104-.642-.158t-.68-.055q-2.093 0-3.546 1.45t-1.453 3.525q-.02.27.01.513t.096.481q-.56.025-1.051.028t-.88.003H12q-1.641 0-3.075-.05q-1.248-.025-2.44-.103q-1.19-.078-1.733-.209q-.516-.136-.865-.496q-.35-.36-.487-.836q-.15-.523-.229-1.262q-.08-.738-.102-1.409q-.05-.805-.05-1.632t.05-1.61q.023-.689.102-1.41q.079-.722.229-1.264q.137-.477.497-.838q.361-.361.855-.495q.562-.15 1.753-.219q1.192-.069 2.418-.108q1.434-.04 3.077-.04");
}

</style>

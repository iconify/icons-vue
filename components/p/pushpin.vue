<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qdl0lnukt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:pushpin" /></template>
<style>
.qdl0lnukt {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18.01 4.929q-.732-.733-1.768-.733q-1.035 0-1.767.733l-1.938 1.938q-.206.206-.49.269l-2.755.612q-1.444.321-1.858 1.741t.633 2.467l1.458 1.459l-4.419 4.419q-.053.052-.094.113t-.069.13t-.043.141t-.014.146t.014.146q.015.073.043.141t.069.13q.041.061.094.113q.105.106.243.163t.287.057t.287-.057t.243-.163l4.419-4.419l1.459 1.458q1.046 1.047 2.467.633q1.42-.414 1.741-1.858l.612-2.755q.063-.284.269-.49l1.938-1.938q.733-.732.733-1.768q0-1.035-.733-1.767z");
}

</style>

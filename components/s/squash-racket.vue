<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cekglo08q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:squash-racket" /></template>
<style>
.cekglo08q {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m4.03 21.03l6.258-6.257q1.583 1.178 3.871.904q2.611-.313 4.658-2.36t2.36-4.658q.325-2.716-1.397-4.44q-1.723-1.721-4.439-1.396q-2.611.313-4.658 2.36t-2.36 4.658q-.274 2.288.904 3.871L2.97 19.97q-.053.052-.094.113t-.069.13t-.043.141t-.014.146q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.105.106.243.163t.287.057t.287-.057t.243-.163m6.751-7.81l-.001-.001q-1.206-1.207-.968-3.199q.252-2.096 1.932-3.776t3.776-1.932q1.992-.238 3.2.969q1.206 1.207.968 3.199q-.252 2.096-1.932 3.776t-3.776 1.932q-1.992.238-3.199-.968");
}

</style>

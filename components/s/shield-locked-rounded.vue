<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dgji2unji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:shield-locked-rounded" /></template>
<style>
.dgji2unji {
  fill: currentColor;
  d: path("M11.705 20.817q-.136-.025-.272-.075q-2.983-1.125-4.708-3.782T5 11.1V6.817q0-.514.293-.926q.292-.412.757-.597l5.385-2q.292-.106.565-.106t.566.106l5.384 2q.464.186.757.597q.293.412.293.926v3.831q0 .354-.251.599t-.624.24q-.95.044-1.812.384t-1.588 1.065q-.675.676-1.075 1.576t-.4 1.95v3.479q0 .288-.197.496q-.197.207-.486.305q-.136.05-.272.075t-.295.025t-.295-.025m4.664.183q-.365 0-.627-.261q-.261-.262-.261-.628v-2.8q0-.35.261-.6q.262-.25.627-.25h.112v-1q0-.748.51-1.258q.511-.51 1.259-.51t1.259.51t.51 1.258v1h.112q.358 0 .613.25q.256.25.256.6v2.8q0 .366-.25.628t-.62.261zm.881-4.538h2v-1q0-.425-.288-.713t-.712-.288t-.712.288t-.288.713z");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r8nxx04kx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:sack" /></template>
<style>
.r8nxx04kx {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m7.279 4.707l.833 2.916q-5.677 3.211-3.84 10.559Q5.164 21.75 12 21.75t7.728-3.568q1.837-7.348-3.84-10.559l.833-2.917q-.017.058-.042.113t-.061.105q-.034.05-.076.094t-.09.081q-.049.036-.103.065q-.053.028-.111.047q-.057.019-.117.029T16 5.25H8q-.061 0-.121-.01q-.059-.01-.117-.029t-.111-.047q-.054-.029-.102-.065q-.049-.037-.091-.08t-.076-.094q-.035-.05-.06-.105q-.026-.055-.043-.113");
}

</style>

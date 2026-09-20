<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j2mkhk-mc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:swap-driving-apps-sharp" /></template>
<style>
.j2mkhk-mc {
  fill: currentColor;
  d: path("m16.154 7.346l-.72-.707l1.6-1.6H7.566v-1h9.468l-1.6-1.6l.708-.72l2.82 2.82zM8.219 17.373q.32-.32.32-.796t-.32-.796t-.796-.32q-.477 0-.796.32t-.32.796t.32.796t.796.32t.796-.32m9.154 0q.32-.32.32-.796t-.32-.796t-.796-.32q-.477 0-.796.32t-.32.796t.32.796t.796.32t.796-.32M4 13.153h14.585L17.112 9H5.946l1.6 1.6l-.708.72L4.02 8.5l2.82-2.82l.707.72l-1.6 1.6H17.84L20 14.154V22h-1.23v-2H5.23v2H4z");
}

</style>

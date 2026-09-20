<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="povig-bpo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:quick-reference-all-outline-sharp" /></template>
<style>
.povig-bpo {
  fill: currentColor;
  d: path("M5 4v6.333v-.025V20zv4zm2.5 9.5h3.596q.148-.287.32-.527q.17-.24.365-.473H7.5zm0 4h2.887q-.053-.25-.07-.5q-.015-.25-.003-.5H7.5zM4 21V3h9.5L18 7.5v3.02q-.244-.086-.494-.121T17 10.333V8h-4V4H5v16h6.39q.186.288.418.533t.486.467zm14.496-2.508q.812-.815.812-1.996t-.816-1.992t-1.996-.812t-1.992.816t-.812 1.996t.816 1.992t1.996.812t1.992-.816m3.104 3.796l-2.777-2.776q-.487.388-1.08.592t-1.243.204q-1.586 0-2.697-1.111t-1.11-2.697t1.11-2.697t2.697-1.11t2.697 1.11t1.11 2.697q0 .65-.203 1.243t-.593 1.08L22.29 21.6z");
}

</style>

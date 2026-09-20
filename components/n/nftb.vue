<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVG8ZBoceqH)" class="gj_20gbji"/><defs><linearGradient id="SVG8ZBoceqH" x1="10.422" x2="17.826" y1="3.804" y2="13.08" gradientUnits="userSpaceOnUse"><stop class="j8zu93bxa"/><stop offset="1" class="a_qxsbc3o"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:nftb" /></template>
<style>
.a_qxsbc3o {
  stop-color: var(--svg-color--de04ff, #de04ff);
}

.ft5dv1b6b {
  fill: none;
}

.gj_20gbji {
  d: path("M17.4 19.8V21H6.6v-1.2zm0-16.8v15.6H6.6V3zm-1.2 1.2H7.8v13.2h8.4z");
}

.j8zu93bxa {
  stop-color: var(--svg-color--18d3fd, #18d3fd);
}

</style>

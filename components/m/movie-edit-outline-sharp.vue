<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s0461ib5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:movie-edit-outline-sharp" /></template>
<style>
.s0461ib5f {
  fill: currentColor;
  d: path("M4 18V9zm-1 1V5h1.616l1.5 3h3l-1.5-3h2l1.5 3h3l-1.5-3h2l1.5 3h3l-1.5-3H21v2.683L19.683 9H4v9h7.846v1zm11.23 1v-2.21l5.96-5.934l2.19 2.204L16.44 20zm6.886-5.94l-.925-.945zm-6 5.056h.95l3.467-3.474l-.47-.475l-.455-.488l-3.492 3.487zm3.948-3.949l-.456-.488l.925.963z");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/m/moy9m_k7d.css';
import '../../css/g/glv0eejpa.css';
import '../../css/u/uo28wmy_e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="moy9m_k7d"/><path class="glv0eejpa"/><path class="uo28wmy_e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:shopping-cart-bold" /></template>

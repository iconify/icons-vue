<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/i1yz4_2hl.css';
import '../../css/w/we8-81bww.css';
import '../../css/p/p7bg0ij5t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="i1yz4_2hl"/><path class="we8-81bww"/><path class="p7bg0ij5t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:sort-amount-up-bold" /></template>

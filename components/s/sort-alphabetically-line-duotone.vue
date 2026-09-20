<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/m/mm06y9blo.css';
import '../../css/v/vnxfpbb2u.css';
import '../../css/e/ez5yvcb0u.css';
import '../../css/u/u65-1ubal.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="mm06y9blo"/><path class="vnxfpbb2u"/><path class="ez5yvcb0u"/><path class="u65-1ubal"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:sort-alphabetically-line-duotone" /></template>

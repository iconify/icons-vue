<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/f/fo6abg74g.css';
import '../../css/u/um2lrkbcl.css';
import '../../css/e/eszr3ewht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="cuyn6tgcc"><path class="fo6abg74g"/><path clip-rule="evenodd" class="um2lrkbcl"/><path class="eszr3ewht"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:shoe-print-bold" /></template>

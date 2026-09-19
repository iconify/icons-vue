<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/g/gd15vvxnd.css';
import '../../css/b/bv5ns8bfe.css';
import '../../css/n/nwa7odbuf.css';
import '../../css/d/dtoswibar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="gd15vvxnd"/><path class="bv5ns8bfe"/><path clip-rule="evenodd" class="nwa7odbuf"/><path class="dtoswibar"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:mallet-bold" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/p/pogviobod.css';
import '../../css/z/zy8ghtbyu.css';
import '../../css/g/gnmfys7zl.css';
import '../../css/f/fc5zd0b4n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="pogviobod"/><path class="zy8ghtbyu"/><path class="gnmfys7zl"/><path class="fc5zd0b4n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:train-outline" /></template>

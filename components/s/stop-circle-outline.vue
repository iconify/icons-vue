<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/p/pgw94f2lz.css';
import '../../css/e/e6qicfbfp.css';
import '../../css/b/bggud1brh.css';
import '../../css/k/kz0_pvboy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="pgw94f2lz"/><path class="e6qicfbfp"/><path class="bggud1brh"/><path class="kz0_pvboy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:stop-circle-outline" /></template>

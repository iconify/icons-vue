<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/a/a4y7rqb1n.css';
import '../../css/e/e6qicfbfp.css';
import '../../css/f/ftyot39ay.css';
import '../../css/k/kz0_pvboy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="a4y7rqb1n"/><path class="e6qicfbfp"/><path class="ftyot39ay"/><path class="kz0_pvboy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:record-outline" /></template>

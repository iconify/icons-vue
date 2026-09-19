<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/e/eemwaab5j.css';
import '../../css/l/l1tjz6bep.css';
import '../../css/l/l3aiq-bqz.css';
import '../../css/b/bi5px2mad.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="eemwaab5j"/><path class="l1tjz6bep"/><path class="l3aiq-bqz"/><path class="bi5px2mad"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:skull-outline" /></template>

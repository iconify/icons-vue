<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/m/mun8-6qsp.css';
import '../../css/v/v5r32fbat.css';
import '../../css/h/hxx-u4vvz.css';
import '../../css/z/zpwhebc3e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="mun8-6qsp"/><path class="v5r32fbat"/><path class="hxx-u4vvz"/><path class="zpwhebc3e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:users-outline" /></template>

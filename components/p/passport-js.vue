<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/u/ul3wxg7ca.css';
import '../../css/p/p5853ld8s.css';
import '../../css/a/a7vsmybvj.css';
import '../../css/w/w0onx4o4e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":400,"height":500};
const content = `<g class="bi12bsetm"><path class="ul3wxg7ca"/><path class="p5853ld8s"/><path class="a7vsmybvj"/><path class="w0onx4o4e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:passport-js" /></template>

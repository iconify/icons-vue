<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/g/gyo39-m2d.css';
import '../../css/s/sokkyvv6c.css';
import '../../css/r/rvn30zbso.css';
import '../../css/s/s9j1rccjl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="gyo39-m2d"/><path class="sokkyvv6c"/><path class="rvn30zbso"/><path class="s9j1rccjl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:object-group-outline" /></template>

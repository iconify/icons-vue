<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/k/kml1eewvt.css';
import '../../css/g/gbvfgr_zm.css';
import '../../css/p/pjwppjbhu.css';
import '../../css/s/sjq61vbaj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="kml1eewvt"/><path class="gbvfgr_zm"/><path class="pjwppjbhu"/><path class="sjq61vbaj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:ruler-trinangle-outline" /></template>

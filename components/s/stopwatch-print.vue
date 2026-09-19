<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/n/nctb2ac4r.css';
import '../../css/e/evccmbbcp.css';
import '../../css/m/mw83ullwt.css';
import '../../css/f/fcht9fhgg.css';
import '../../css/j/jfl6vdt6u.css';
import '../../css/n/nv2kmwbep.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><g class="nctb2ac4r"><path class="evccmbbcp"/><path clip-rule="evenodd" class="mw83ullwt"/></g><path clip-rule="evenodd" class="fcht9fhgg"/><path clip-rule="evenodd" class="jfl6vdt6u"/><path clip-rule="evenodd" class="nv2kmwbep"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:stopwatch-print" /></template>

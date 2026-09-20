<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/t/tp4039bga.css';
import '../../css/q/q5mw45mda.css';
import '../../css/j/jit7z08of.css';
import '../../css/r/r_jkair3d.css';
import '../../css/d/dos-n8l3o.css';
import '../../css/k/knax3bcoe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="ft5dv1b6b"><path class="tp4039bga"/><path class="q5mw45mda"/><path clip-rule="evenodd" class="jit7z08of"/><path class="r_jkair3d"/><path class="dos-n8l3o"/><path class="knax3bcoe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pencil:printer" /></template>

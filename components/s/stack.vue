<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/l/ld-vaf42i.css';
import '../../css/d/d70hihddh.css';
import '../../css/h/hr2s4cbop.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ld-vaf42i"/><path class="d70hihddh"/><path class="hr2s4cbop"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:stack" /></template>

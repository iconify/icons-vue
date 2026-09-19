<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/q/qs6hszyma.css';
import '../../css/b/b8nviyb0p.css';
import '../../css/o/osuz1epzg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qs6hszyma"/><path class="b8nviyb0p"/><path class="osuz1epzg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:shuffle" /></template>

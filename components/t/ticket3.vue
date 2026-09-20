<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/q/qm9f-1b5j.css';
import '../../css/m/m0pr6ebgc.css';
import '../../css/f/fhaiddqfm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qm9f-1b5j"/><path class="m0pr6ebgc"/><path class="fhaiddqfm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:ticket3" /></template>

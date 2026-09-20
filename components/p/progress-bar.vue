<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/n/n51hvo05m.css';
import '../../css/p/pir0p8iya.css';
import '../../css/x/x5__mybwz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="n51hvo05m"/><rect class="pir0p8iya"/><path class="x5__mybwz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:progress-bar" /></template>

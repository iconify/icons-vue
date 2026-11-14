<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/b/b22cvxy9q.css';
import '../../css/s/sea5vybym.css';
import '../../css/r/raype-70g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="b22cvxy9q"/><path class="sea5vybym"/><path class="raype-70g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:tips" /></template>

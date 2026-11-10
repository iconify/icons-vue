<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/odx1occis.css';
import '../../css/x/xflj7b96n.css';
import '../../css/i/ik7t6gbzg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="odx1occis"><path class="xflj7b96n"/><path class="ik7t6gbzg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="matita:rotate-ccw" /></template>

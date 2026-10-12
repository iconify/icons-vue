<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/x/xsm08abtz.css';
import '../../css/r/rvmewzb1s.css';
import '../../css/c/curhonbwt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="xsm08abtz"/><path class="rvmewzb1s"/><path class="curhonbwt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:vector-square-duotone" /></template>

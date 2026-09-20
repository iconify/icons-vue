<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/r/r7bwjtgfs.css';
import '../../css/h/hkt1xxbem.css';
import '../../css/m/mc2zb0bvp.css';
import '../../css/r/r7_340bul.css';
import '../../css/z/zul9ixm_v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="r7bwjtgfs"/><path class="hkt1xxbem"/><g class="mc2zb0bvp"><path class="r7_340bul"/><path class="zul9ixm_v"/></g></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:paint-roller-bold-duotone" /></template>

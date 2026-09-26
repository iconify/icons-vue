<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/z/zjdu56bfc.css';
import '../../css/t/tds357sde.css';
import '../../css/m/m2_y5b4pz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="zjdu56bfc"/><path class="tds357sde"/><path class="m2_y5b4pz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:separator-horizontal-outline" /></template>

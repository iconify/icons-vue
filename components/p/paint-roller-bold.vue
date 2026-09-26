<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/r/r7bwjtgfs.css';
import '../../css/i/iuqg7ob6n.css';
import '../../css/h/hkt1xxbem.css';
import '../../css/m/m7byn6b2f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="r7bwjtgfs"/><path class="iuqg7ob6n"/><path class="hkt1xxbem"/><path class="m7byn6b2f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:paint-roller-bold" /></template>

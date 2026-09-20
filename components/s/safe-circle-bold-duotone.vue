<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/o/oz-bic4ri.css';
import '../../css/n/np8hs5bqz.css';
import '../../css/e/esbwh55ly.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="oz-bic4ri"/><path clip-rule="evenodd" class="np8hs5bqz"/><path class="esbwh55ly"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:safe-circle-bold-duotone" /></template>

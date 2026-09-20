<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/p/p14up0_ne.css';
import '../../css/t/tj9p9h5bc.css';
import '../../css/u/uxdowbokt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="p14up0_ne"/><path class="tj9p9h5bc"/><path class="uxdowbokt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:text-cross-outline" /></template>

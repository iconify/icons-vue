<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/u/u40pfubrp.css';
import '../../css/m/ma-oqebnh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="u40pfubrp"/><path clip-rule="evenodd" class="ma-oqebnh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:minimalistic-magnifier-zoom-in-bold" /></template>

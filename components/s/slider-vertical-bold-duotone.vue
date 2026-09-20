<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/k/kwlqebc6h.css';
import '../../css/m/mc2zb0bvp.css';
import '../../css/j/jejndwbfp.css';
import '../../css/x/xpb82nibn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="kwlqebc6h"/><g class="mc2zb0bvp"><path class="jejndwbfp"/><path class="xpb82nibn"/></g></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:slider-vertical-bold-duotone" /></template>

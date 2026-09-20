<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/a/algz9sbaz.css';
import '../../css/u/u334qkbzc.css';
import '../../css/b/bve6fnunb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="algz9sbaz"/><path clip-rule="evenodd" class="u334qkbzc"/><path class="bve6fnunb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:slider-minimalistic-horizontal-outline" /></template>

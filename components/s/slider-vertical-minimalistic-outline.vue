<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/s/s9r4-h63l.css';
import '../../css/z/zoh7-268d.css';
import '../../css/d/dkcoat2_r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="s9r4-h63l"/><path class="zoh7-268d"/><path class="dkcoat2_r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:slider-vertical-minimalistic-outline" /></template>

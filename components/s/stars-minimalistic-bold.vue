<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/c/chjn_i6rt.css';
import '../../css/c/czv0ewbne.css';
import '../../css/g/g8k88bb_r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="chjn_i6rt"/><path class="czv0ewbne"/><path class="g8k88bb_r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:stars-minimalistic-bold" /></template>

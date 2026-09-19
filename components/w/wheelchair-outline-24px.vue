<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/i/iqvs1ctqv.css';
import '../../css/r/rqpnbwxgn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="iqvs1ctqv"/><path clip-rule="evenodd" class="rqpnbwxgn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:wheelchair-outline-24px" /></template>

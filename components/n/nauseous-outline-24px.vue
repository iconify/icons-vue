<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/g/g1ysqtbqm.css';
import '../../css/t/tbvtb7bkt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="g1ysqtbqm"/><path clip-rule="evenodd" class="tbvtb7bkt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:nauseous-outline-24px" /></template>

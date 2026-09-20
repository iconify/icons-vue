<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/x/xg1lcnbpv.css';
import '../../css/e/en376_own.css';
import '../../css/d/dk_5p9bho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="xg1lcnbpv"/><path clip-rule="evenodd" class="en376_own"/><path class="dk_5p9bho"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:translate2-filled" /></template>

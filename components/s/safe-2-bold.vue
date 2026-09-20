<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/a/aolcgbcee.css';
import '../../css/u/uqmgy3bvg.css';
import '../../css/l/lnc15sjoj.css';
import '../../css/g/g4ti84arf.css';
import '../../css/h/hg6y6kfxq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="aolcgbcee"/><path class="uqmgy3bvg"/><path class="lnc15sjoj"/><path clip-rule="evenodd" class="g4ti84arf"/><path clip-rule="evenodd" class="hg6y6kfxq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:safe-2-bold" /></template>

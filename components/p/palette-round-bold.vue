<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/t/t23fxacvf.css';
import '../../css/z/zegrxibpg.css';
import '../../css/f/f6ck3roek.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="t23fxacvf"/><path class="zegrxibpg"/><path clip-rule="evenodd" class="f6ck3roek"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:palette-round-bold" /></template>

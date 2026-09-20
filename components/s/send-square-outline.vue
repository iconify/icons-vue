<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/e/esbwh55ly.css';
import '../../css/t/t99s0f6ww.css';
import '../../css/z/zuqh_gv5l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="esbwh55ly"/><path class="t99s0f6ww"/><path clip-rule="evenodd" class="zuqh_gv5l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:send-square-outline" /></template>

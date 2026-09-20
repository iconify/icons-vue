<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/g/g_n-lsb4d.css';
import '../../css/t/tpngthz3k.css';
import '../../css/i/ibj2xggkh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="g_n-lsb4d"/><path class="tpngthz3k"/><path clip-rule="evenodd" class="ibj2xggkh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:shield-warning-outline" /></template>

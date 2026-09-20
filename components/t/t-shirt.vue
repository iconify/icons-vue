<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/m/m5kx_zt5a.css';
import '../../css/d/df_1v7hrx.css';
import '../../css/a/axk82gbzf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="m5kx_zt5a"/><path clip-rule="evenodd" class="df_1v7hrx"/><path class="axk82gbzf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-print:t-shirt" /></template>

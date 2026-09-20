<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/c/cuiniwbro.css';
import '../../css/j/jlcyzeb2p.css';
import '../../css/r/r5ykmgbft.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="cuiniwbro"/><path class="jlcyzeb2p"/><path clip-rule="evenodd" class="r5ykmgbft"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pencil:money-note" /></template>

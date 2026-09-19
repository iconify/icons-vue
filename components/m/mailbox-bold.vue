<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/b/bplyu_bdz.css';
import '../../css/t/t_dv8acgh.css';
import '../../css/t/txr5u1n8b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="bplyu_bdz"/><path class="t_dv8acgh"/><path clip-rule="evenodd" class="txr5u1n8b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:mailbox-bold" /></template>

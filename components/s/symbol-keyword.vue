<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/n/np53o28bd.css';
import '../../css/c/cvi0tubrb.css';
import '../../css/y/ywsaehxql.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="np53o28bd"/><path clip-rule="evenodd" class="cvi0tubrb"/><path class="ywsaehxql"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:symbol-keyword" /></template>

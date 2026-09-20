<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/c/cdtq3ubbc.css';
import '../../css/w/wq-6doxql.css';
import '../../css/c/cl-6xabrp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="cdtq3ubbc"/><path class="wq-6doxql"/><path clip-rule="evenodd" class="cl-6xabrp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:user-id" /></template>

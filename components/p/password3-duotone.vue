<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/e/ehjdnrb9a.css';
import '../../css/d/dc1veeb1p.css';
import '../../css/r/rlin_rb8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ehjdnrb9a"/><path class="dc1veeb1p"/><path clip-rule="evenodd" class="rlin_rb8a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:password3-duotone" /></template>

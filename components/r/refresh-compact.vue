<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/a/as-0c8b1d.css';
import '../../css/n/ngboggbka.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<g class="cuyn6tgcc"><path class="as-0c8b1d"/><path class="ngboggbka"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:refresh-compact" /></template>

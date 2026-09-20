<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/lwfoszbft.css';
import '../../css/x/xlh4q9b7n.css';
import '../../css/x/xsj74acax.css';
import '../../css/w/wpmbaftjs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="lwfoszbft"/><path class="xlh4q9b7n"/><path clip-rule="evenodd" class="xsj74acax"/><path clip-rule="evenodd" class="wpmbaftjs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:stars-line-outline" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/o/otiz8qbou.css';
import '../../css/s/s2qmknl-c.css';
import '../../css/b/bz-nx6b1k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="otiz8qbou"/><path class="s2qmknl-c"/><path clip-rule="evenodd" class="bz-nx6b1k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:taxi" /></template>

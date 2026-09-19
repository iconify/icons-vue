<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/u/uh1g6cz1h.css';
import '../../css/n/n8mw7qbiz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="uh1g6cz1h"/><path clip-rule="evenodd" class="n8mw7qbiz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:ppe-mask-outline-24px" /></template>

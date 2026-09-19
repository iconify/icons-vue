<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/b/bu6ztne7y.css';
import '../../css/u/uy9n4bczz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="bu6ztne7y"/><path clip-rule="evenodd" class="uy9n4bczz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:rdt-result-out-stock2x-outline" /></template>

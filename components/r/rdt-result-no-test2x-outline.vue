<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/e/ee9q2291t.css';
import '../../css/s/sgd0ieb1h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="ee9q2291t"/><path clip-rule="evenodd" class="sgd0ieb1h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:rdt-result-no-test2x-outline" /></template>

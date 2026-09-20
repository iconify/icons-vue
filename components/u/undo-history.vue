<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/g/ge_-4ubim.css';
import '../../css/n/n2h6fyjip.css';
import '../../css/l/l4j1qrodv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<g class="bi12bsetm"><path class="ge_-4ubim"/><path class="n2h6fyjip"/><path class="l4j1qrodv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:undo-history" /></template>

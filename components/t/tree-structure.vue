<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e0i398m6x.css';
import '../../css/a/ay6c3pb8e.css';
import '../../css/m/msp76tw5p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="e0i398m6x"/><path class="ay6c3pb8e"/><path class="msp76tw5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:tree-structure" /></template>

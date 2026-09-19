<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h01tyzbfu.css';
import '../../css/v/v8t7a0big.css';
import '../../css/q/qxv7eobba.css';
import '../../css/t/tmt8sqbls.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><path class="v8t7a0big"/><path class="qxv7eobba"/><path class="tmt8sqbls"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:wrench-01" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xck5rbc3z.css';
import '../../css/d/d9ipvbcrp.css';
import '../../css/d/dfk6wqbuw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="xck5rbc3z"><path clip-rule="evenodd" class="d9ipvbcrp"/><path class="dfk6wqbuw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:voice-scan-1" /></template>

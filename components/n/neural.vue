<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9cl3zbei.css';
import '../../css/l/lnyuaxrwt.css';
import '../../css/t/t69oulbwo.css';
import '../../css/a/az25568cs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="s9cl3zbei"><path clip-rule="evenodd" class="lnyuaxrwt"/><path class="t69oulbwo"/><path class="az25568cs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:neural" /></template>

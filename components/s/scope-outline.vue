<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/l/lk35y-bvr.css';
import '../../css/c/cn5-l9bdz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="scope-outline"><g class="Vector n1lsf0bnc" clip-rule="evenodd"><path class="lk35y-bvr"/><path class="cn5-l9bdz"/></g></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cuida:scope-outline" /></template>

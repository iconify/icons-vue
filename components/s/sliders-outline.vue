<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/z/zbehsk69m.css';
import '../../css/e/evwpmfbcj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="sliders-outline"><g class="Vector n1lsf0bnc" clip-rule="evenodd"><path class="zbehsk69m"/><path class="evwpmfbcj"/></g></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cuida:sliders-outline" /></template>

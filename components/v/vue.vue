<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qfttfe_2y.css';
import '../../css/v/vt5inqbvm.css';
import '../../css/w/w7622wbzz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="qfttfe_2y"><path class="vt5inqbvm"/><path class="w7622wbzz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:vue" /></template>

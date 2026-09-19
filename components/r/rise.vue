<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/g/g99su5_wf.css';
import '../../css/s/s_lsgrezf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="bi12bsetm"><circle class="g99su5_wf"/><path class="s_lsgrezf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency-color:rise" /></template>

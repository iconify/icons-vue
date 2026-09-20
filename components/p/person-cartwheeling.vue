<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x4u8pbwjc.css';
import '../../css/h/hhvthyu9m.css';
import '../../css/f/ftf_v_bxo.css';
import '../../css/x/x8poo_bjf.css';
import '../../css/c/cgxswbbyp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<g class="x4u8pbwjc"><circle class="hhvthyu9m"/><path class="ftf_v_bxo"/></g><g class="x8poo_bjf"><circle class="hhvthyu9m"/><path class="cgxswbbyp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:person-cartwheeling" /></template>

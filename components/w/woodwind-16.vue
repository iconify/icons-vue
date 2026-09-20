<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dwszy3bem.css';
import '../../css/o/ovjr3gbvd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="dwszy3bem"/><path class="ovjr3gbvd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:woodwind-16" /></template>

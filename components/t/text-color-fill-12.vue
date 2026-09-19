<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fpifswb1p.css';
import '../../css/c/cuadd06uu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="fpifswb1p"/><path class="cuadd06uu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:text-color-fill-12" /></template>

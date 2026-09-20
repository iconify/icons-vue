<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ti1uxtajd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path paint-order="stroke fill markers" class="ti1uxtajd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:quarto" /></template>

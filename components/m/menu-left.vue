<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/csm2fgbbt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="csm2fgbbt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:menu-left" /></template>

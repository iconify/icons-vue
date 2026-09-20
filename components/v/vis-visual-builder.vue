<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d4chyzbwv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="d4chyzbwv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:vis-visual-builder" /></template>

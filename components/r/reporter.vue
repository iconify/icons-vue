<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ek2c01bmu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ek2c01bmu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:reporter" /></template>

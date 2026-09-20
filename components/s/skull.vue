<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eac1_7euy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="eac1_7euy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:skull" /></template>

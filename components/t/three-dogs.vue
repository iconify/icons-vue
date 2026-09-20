<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i24d3zwii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="i24d3zwii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:three-dogs" /></template>

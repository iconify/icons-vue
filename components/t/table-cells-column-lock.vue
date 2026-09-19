<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nbv4uiyrx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="nbv4uiyrx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:table-cells-column-lock" /></template>

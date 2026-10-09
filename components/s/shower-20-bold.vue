<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v1ddg9bac.css';
import '../../css/a/a2s7bl5_y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="v1ddg9bac"/><path class="a2s7bl5_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:shower-20-bold" /></template>

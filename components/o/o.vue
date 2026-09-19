<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ez447-bmb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="ez447-bmb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:o" /></template>

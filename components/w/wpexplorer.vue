<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/modf53ylu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="modf53ylu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:wpexplorer" /></template>

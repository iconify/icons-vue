<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ki_r4_mpr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="ki_r4_mpr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:person-booth" /></template>

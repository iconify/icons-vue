<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kcc10c5ah.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="kcc10c5ah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:square-git" /></template>

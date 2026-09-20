<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e0i21wz3b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="e0i21wz3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:processing" /></template>

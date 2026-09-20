<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l25-asbjw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="l25-asbjw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:slim" /></template>

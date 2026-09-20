<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r4s6-81zn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="r4s6-81zn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:prisma" /></template>

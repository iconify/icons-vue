<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mtcavo2ye.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mtcavo2ye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:textalign-justifycenter-filled" /></template>

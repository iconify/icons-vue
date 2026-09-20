<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jb39vdkqu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jb39vdkqu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:rhombus" /></template>

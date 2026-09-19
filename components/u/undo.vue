<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qqgpeml1y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":24};
const content = `<path class="qqgpeml1y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:undo" /></template>

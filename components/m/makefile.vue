<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q1nmcuu0y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="q1nmcuu0y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:makefile" /></template>

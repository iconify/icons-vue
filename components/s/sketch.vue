<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oxo0sinma.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oxo0sinma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:sketch" /></template>

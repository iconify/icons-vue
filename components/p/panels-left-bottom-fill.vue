<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cc5-p1byx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cc5-p1byx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:panels-left-bottom-fill" /></template>

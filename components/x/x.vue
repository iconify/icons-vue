<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fsl8lxbnu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fsl8lxbnu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:x" /></template>

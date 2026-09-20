<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v07v--l5k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v07v--l5k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:volume-x" /></template>

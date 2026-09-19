<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dwv858cch.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dwv858cch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:php" /></template>

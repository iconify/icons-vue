<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/udqirj5ye.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="udqirj5ye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:vector-difference-ba" /></template>

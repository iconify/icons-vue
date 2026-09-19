<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xlenj-bjm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="xlenj-bjm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:tmux" /></template>

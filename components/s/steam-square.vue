<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jz207_u2f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="jz207_u2f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:steam-square" /></template>

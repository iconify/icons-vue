<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j51sodbls.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="j51sodbls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:stylelint" /></template>

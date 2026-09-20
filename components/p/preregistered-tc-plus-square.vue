<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kr85fxbsu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="kr85fxbsu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="academicons:preregistered-tc-plus-square" /></template>

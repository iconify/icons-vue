<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uo8189bjo.css';
import '../../css/v/v0h1tybbc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="uo8189bjo"/><path clip-rule="evenodd" class="v0h1tybbc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:warning-32" /></template>

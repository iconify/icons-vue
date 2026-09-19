<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kppwirbvh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="kppwirbvh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:uni8d5e-box" /></template>

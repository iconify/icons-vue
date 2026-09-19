<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gz9vf6d5q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="gz9vf6d5q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:smiling-face-with-heart-shaped-eyes" /></template>

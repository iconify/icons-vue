<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/csg07lgga.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="csg07lgga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:movie-camera" /></template>

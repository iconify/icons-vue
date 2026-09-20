<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s98b-2bjf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="s98b-2bjf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:sedan-under-taxi-checkerboard" /></template>

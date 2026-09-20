<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w7g600yaa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="w7g600yaa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:motorcycle-under-taxi-checkerboard" /></template>

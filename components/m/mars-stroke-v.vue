<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bkyf5esrh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":24};
const content = `<path class="bkyf5esrh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:mars-stroke-v" /></template>

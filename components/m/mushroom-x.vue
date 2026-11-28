<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r4hauzmfj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r4hauzmfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:mushroom-x" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mi44fdc-q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mi44fdc-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:three-stars-solid" /></template>

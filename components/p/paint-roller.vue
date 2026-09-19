<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jjxm42wfj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jjxm42wfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:paint-roller" /></template>

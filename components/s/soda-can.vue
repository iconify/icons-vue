<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y22fbc5xj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="y22fbc5xj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:soda-can" /></template>

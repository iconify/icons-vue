<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y6banzb4e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="y6banzb4e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:mailed-fist" /></template>

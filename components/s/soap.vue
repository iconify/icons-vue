<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fjn7tl86z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fjn7tl86z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:soap" /></template>

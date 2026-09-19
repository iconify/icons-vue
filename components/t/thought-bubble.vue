<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ycm4o3bok.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ycm4o3bok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:thought-bubble" /></template>

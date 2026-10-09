<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/clgzsub0s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="clgzsub0s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:user-cog-20-bold" /></template>

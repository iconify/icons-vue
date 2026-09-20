<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/poig4bcxz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="poig4bcxz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:utensils-spoon" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/ju8vq4b2y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ju8vq4b2y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:steps-down" /></template>

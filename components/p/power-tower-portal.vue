<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yp3qq1znw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="yp3qq1znw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:power-tower-portal" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pomm0gk9g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="pomm0gk9g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:star" /></template>

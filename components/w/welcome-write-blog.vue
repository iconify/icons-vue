<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m-8wrey9z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="m-8wrey9z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:welcome-write-blog" /></template>

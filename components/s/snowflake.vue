<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bmb4kccad.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="bmb4kccad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:snowflake" /></template>

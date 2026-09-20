<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f16bk7bqf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":310};
const content = `<path class="f16bk7bqf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:prisma-dark" /></template>

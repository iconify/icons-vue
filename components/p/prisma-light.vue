<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r3m2ftunn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":310};
const content = `<path class="r3m2ftunn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:prisma-light" /></template>

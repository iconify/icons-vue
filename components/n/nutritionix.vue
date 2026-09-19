<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bvayc7r2n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="bvayc7r2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:nutritionix" /></template>

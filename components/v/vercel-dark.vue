<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lv5f08b2c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":222};
const content = `<path class="lv5f08b2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:vercel-dark" /></template>

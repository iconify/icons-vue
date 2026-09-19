<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y_qdteboe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="y_qdteboe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:sitrox" /></template>

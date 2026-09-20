<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z0d_yj6xx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z0d_yj6xx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:vectary" /></template>

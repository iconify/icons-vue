<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pomm6baka.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pomm6baka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:mongoose" /></template>

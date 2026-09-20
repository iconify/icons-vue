<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y_y4od_0v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y_y4od_0v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:trophy" /></template>

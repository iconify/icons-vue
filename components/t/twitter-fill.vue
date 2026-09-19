<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y3syncdfl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y3syncdfl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:twitter-fill" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o8bmtiblz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o8bmtiblz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:sun" /></template>

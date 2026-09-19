<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hjs1_he5e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hjs1_he5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:snow" /></template>

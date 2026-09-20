<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fp4d-sb3o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fp4d-sb3o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:paint-roller-linear" /></template>

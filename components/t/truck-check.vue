<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l-3o6lbxy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l-3o6lbxy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:truck-check" /></template>

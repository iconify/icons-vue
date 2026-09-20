<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d9_m2xuuj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d9_m2xuuj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:opel" /></template>

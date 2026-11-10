<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k6jdc4bgb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k6jdc4bgb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:n8n" /></template>

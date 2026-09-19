<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d-8f8cbaq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d-8f8cbaq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:presentation" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dx5dv8bho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dx5dv8bho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:pencil-ruler-outline" /></template>

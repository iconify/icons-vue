<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m7d196oys.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m7d196oys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:sort-alphabet-asc" /></template>

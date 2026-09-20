<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ugnvysp9f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ugnvysp9f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:mixtral-fill" /></template>

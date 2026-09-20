<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x5cc4gltw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x5cc4gltw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:unsplash-fill" /></template>

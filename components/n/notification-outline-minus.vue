<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mltf9q9oz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mltf9q9oz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:notification-outline-minus" /></template>

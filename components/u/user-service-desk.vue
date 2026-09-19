<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/khutn8b6n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="khutn8b6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:user-service-desk" /></template>

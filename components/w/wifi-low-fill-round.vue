<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dfxg86bow.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dfxg86bow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:wifi-low-fill-round" /></template>

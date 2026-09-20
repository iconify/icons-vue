<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e9q1w35vn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e9q1w35vn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:spotlight-sharp" /></template>

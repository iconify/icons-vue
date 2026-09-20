<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e9qg5-jrw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e9qg5-jrw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:unlink-sharp" /></template>

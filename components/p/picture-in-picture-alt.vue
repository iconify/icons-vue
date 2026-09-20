<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zlzazsb2b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zlzazsb2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:picture-in-picture-alt" /></template>

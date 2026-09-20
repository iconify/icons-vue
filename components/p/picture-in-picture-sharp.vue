<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ozxky6mjf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ozxky6mjf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:picture-in-picture-sharp" /></template>

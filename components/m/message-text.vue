<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gfqch5byy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gfqch5byy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:message-text" /></template>

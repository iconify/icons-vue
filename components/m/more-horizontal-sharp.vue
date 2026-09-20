<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lsb22-d5r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lsb22-d5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:more-horizontal-sharp" /></template>

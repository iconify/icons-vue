<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wcrccabpq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wcrccabpq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:vibrate-sharp" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dtg7lpbko.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dtg7lpbko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:thumbs-up-sharp" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/swzcg5bau.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="swzcg5bau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:thumbs-down-sharp" /></template>

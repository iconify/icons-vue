<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/isrxau9wl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="isrxau9wl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:shield-sharp" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c180_r4qr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c180_r4qr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:sunset-duotone-round" /></template>

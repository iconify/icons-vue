<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rgix3bcvw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rgix3bcvw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:wand-solid" /></template>

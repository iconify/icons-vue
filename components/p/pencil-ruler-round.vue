<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j6_ymacif.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j6_ymacif"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:pencil-ruler-round" /></template>

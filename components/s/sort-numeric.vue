<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ud2kccwkc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ud2kccwkc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:sort-numeric" /></template>

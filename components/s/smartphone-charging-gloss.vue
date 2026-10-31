<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kecnv9bfy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kecnv9bfy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:smartphone-charging-gloss" /></template>

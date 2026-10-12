<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gdz78pbas.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gdz78pbas"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:rectangle-vertical-filled" /></template>

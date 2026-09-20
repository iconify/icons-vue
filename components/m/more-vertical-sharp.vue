<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ll6enqb7y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ll6enqb7y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:more-vertical-sharp" /></template>

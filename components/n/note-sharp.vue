<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r--agl2sm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r--agl2sm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:note-sharp" /></template>

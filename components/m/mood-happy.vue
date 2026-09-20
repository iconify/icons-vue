<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zuqyrrbgs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zuqyrrbgs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:mood-happy" /></template>

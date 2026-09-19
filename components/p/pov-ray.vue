<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rv8vgf7uy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":371,"height":512};
const content = `<path class="rv8vgf7uy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:pov-ray" /></template>

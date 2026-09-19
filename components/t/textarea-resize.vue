<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wcthy1uug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="wcthy1uug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:textarea-resize" /></template>

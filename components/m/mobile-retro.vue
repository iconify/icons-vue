<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vyl-3tbdi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="vyl-3tbdi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:mobile-retro" /></template>

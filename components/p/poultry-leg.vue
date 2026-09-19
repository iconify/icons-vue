<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w3g89ob7z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="w3g89ob7z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:poultry-leg" /></template>

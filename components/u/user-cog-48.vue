<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wasq8zbwi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wasq8zbwi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:user-cog-48" /></template>

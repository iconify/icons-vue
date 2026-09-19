<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y6jyvwbbs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="y6jyvwbbs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:moon-outline" /></template>

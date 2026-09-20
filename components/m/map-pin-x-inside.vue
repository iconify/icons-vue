<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sg5wtwb9f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sg5wtwb9f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:map-pin-x-inside" /></template>

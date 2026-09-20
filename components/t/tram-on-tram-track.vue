<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ulu6lsb-z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ulu6lsb-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:tram-on-tram-track" /></template>

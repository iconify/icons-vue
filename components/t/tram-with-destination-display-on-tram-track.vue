<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h3fuerh2q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="h3fuerh2q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:tram-with-destination-display-on-tram-track" /></template>

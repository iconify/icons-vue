<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sevo_kb4p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sevo_kb4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:mapbox" /></template>

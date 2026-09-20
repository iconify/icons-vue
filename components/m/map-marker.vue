<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/knrawyb7o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="knrawyb7o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:map-marker" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dljs7lzik.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dljs7lzik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:smart-card-reader-outline" /></template>

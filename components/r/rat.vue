<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n5uez4b9h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n5uez4b9h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:rat" /></template>

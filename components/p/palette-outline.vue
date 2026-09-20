<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/flwpjz0pz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="flwpjz0pz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:palette-outline" /></template>

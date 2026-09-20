<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/islj7dbok.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="islj7dbok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:panorama-outline" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s19nmm6ry.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s19nmm6ry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:mobile-off" /></template>

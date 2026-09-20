<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w0z0gubss.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w0z0gubss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:skip-previous-circle" /></template>

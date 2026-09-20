<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pj1lizb5e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pj1lizb5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:reorder-vertical" /></template>

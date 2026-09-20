<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w59t3iw6h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w59t3iw6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:numbers-3" /></template>

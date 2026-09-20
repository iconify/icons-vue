<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vgve4ur3u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vgve4ur3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:tv-old-line" /></template>

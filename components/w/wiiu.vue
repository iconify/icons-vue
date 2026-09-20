<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d3r3u6_tg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d3r3u6_tg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:wiiu" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z-qgs2bow.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z-qgs2bow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:remote-tv-off" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yaj_g9blf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yaj_g9blf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:pan-up-left" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mmh5xvb-x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mmh5xvb-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:scroll-text-outline" /></template>

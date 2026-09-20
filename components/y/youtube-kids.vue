<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vaumwsb0s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vaumwsb0s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:youtube-kids" /></template>

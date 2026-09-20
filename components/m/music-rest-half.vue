<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g21co_blw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g21co_blw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:music-rest-half" /></template>

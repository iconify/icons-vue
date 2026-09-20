<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/snaob0bev.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="snaob0bev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:thunderstorm-sun" /></template>

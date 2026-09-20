<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vsza4_yqi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vsza4_yqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:movie-2-fill" /></template>

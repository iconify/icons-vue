<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r7usczbwu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r7usczbwu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:netease-cloud-music-fill" /></template>

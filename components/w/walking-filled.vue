<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yt_demb3i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yt_demb3i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:walking-filled" /></template>

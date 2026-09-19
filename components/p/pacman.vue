<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uqnu7xbid.css';
import '../../css/f/fw-cofgvd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uqnu7xbid"/><path class="fw-cofgvd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:pacman" /></template>

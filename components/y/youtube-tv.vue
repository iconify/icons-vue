<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yl4nvpb4x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yl4nvpb4x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:youtube-tv" /></template>

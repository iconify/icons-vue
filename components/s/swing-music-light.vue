<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tz97kebhr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tz97kebhr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:swing-music-light" /></template>

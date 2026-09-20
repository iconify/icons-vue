<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bswknnbyu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bswknnbyu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:video-1" /></template>

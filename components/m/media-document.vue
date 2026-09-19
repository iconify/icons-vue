<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sfc5vfbmg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="sfc5vfbmg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:media-document" /></template>

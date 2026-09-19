<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kvj4naczm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1280};
const content = `<path class="kvj4naczm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:youtube-play" /></template>

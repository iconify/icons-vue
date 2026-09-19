<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nwtf473fh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nwtf473fh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:scan-text" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n5ewujben.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="n5ewujben"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:microsoft-access" /></template>

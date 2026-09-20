<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zmv4w6tgg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zmv4w6tgg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:rectangle-4" /></template>

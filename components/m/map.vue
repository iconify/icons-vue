<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/him3u7bwy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="him3u7bwy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:map" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xbp1jcc3o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xbp1jcc3o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:round-arrow-2" /></template>

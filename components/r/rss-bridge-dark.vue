<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wgil3hbqk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wgil3hbqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:rss-bridge-dark" /></template>

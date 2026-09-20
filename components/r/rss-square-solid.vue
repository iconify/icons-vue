<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/woxf2db7d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="woxf2db7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:rss-square-solid" /></template>

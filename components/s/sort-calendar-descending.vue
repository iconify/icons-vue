<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yt7ejub1l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yt7ejub1l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:sort-calendar-descending" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pi3u4bkjb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pi3u4bkjb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:recycle-03" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wj-4iw7vd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wj-4iw7vd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:music-off" /></template>

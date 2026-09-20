<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mh7ffuh6k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mh7ffuh6k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:subtitles-outline" /></template>

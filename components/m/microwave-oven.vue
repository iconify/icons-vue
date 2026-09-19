<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mpd4zl64s.css';
import '../../css/w/w9yaz1b7p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mpd4zl64s"/><path class="w9yaz1b7p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:microwave-oven" /></template>

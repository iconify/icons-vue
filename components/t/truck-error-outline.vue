<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/byt-hfbpa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="byt-hfbpa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:truck-error-outline" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e8l01g8ad.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e8l01g8ad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:surround-sound-5-1" /></template>

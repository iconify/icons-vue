<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nhl-ulblf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nhl-ulblf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:timelapse" /></template>

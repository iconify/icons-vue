<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yko8wbc2a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yko8wbc2a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:smart-watch-square-heart-bold" /></template>

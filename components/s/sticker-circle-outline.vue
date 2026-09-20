<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q3lrixbci.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q3lrixbci"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:sticker-circle-outline" /></template>

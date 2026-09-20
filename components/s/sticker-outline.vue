<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o3x5mfbar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o3x5mfbar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:sticker-outline" /></template>

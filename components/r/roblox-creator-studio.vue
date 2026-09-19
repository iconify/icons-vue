<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vq1zcxy1w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="vq1zcxy1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:roblox-creator-studio" /></template>

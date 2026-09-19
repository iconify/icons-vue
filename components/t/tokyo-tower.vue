<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/of-jukbpg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="of-jukbpg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:tokyo-tower" /></template>

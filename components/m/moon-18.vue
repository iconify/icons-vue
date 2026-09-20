<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rl-bsbz7w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="rl-bsbz7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:moon-18" /></template>

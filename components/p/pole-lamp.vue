<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vo3u11b1i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vo3u11b1i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:pole-lamp" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u4no5ubeq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="u4no5ubeq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:volume-mute-fill" /></template>

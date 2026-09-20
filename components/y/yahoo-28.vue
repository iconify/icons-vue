<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w774m13-a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="w774m13-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:yahoo-28" /></template>

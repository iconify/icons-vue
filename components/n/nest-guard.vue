<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wjnyjob-l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="wjnyjob-l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:nest-guard" /></template>

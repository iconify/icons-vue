<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fpvrhkuig.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fpvrhkuig"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:sort-up" /></template>

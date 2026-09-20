<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w7jx49xst.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w7jx49xst"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:news-paper-remix" /></template>

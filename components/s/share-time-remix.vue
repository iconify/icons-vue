<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ly7o7ggfz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ly7o7ggfz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:share-time-remix" /></template>

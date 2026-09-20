<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ns8ydacjd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ns8ydacjd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:suitcase-lines-outline" /></template>

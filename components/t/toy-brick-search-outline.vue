<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r6r397xvd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r6r397xvd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:toy-brick-search-outline" /></template>

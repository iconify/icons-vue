<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wljsz2b4v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wljsz2b4v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:timeline-event-text" /></template>

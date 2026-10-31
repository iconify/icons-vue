<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iqsvpyspo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iqsvpyspo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-arrow-down-left-fill-round" /></template>

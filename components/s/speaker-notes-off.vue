<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wqfprac4i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wqfprac4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:speaker-notes-off" /></template>

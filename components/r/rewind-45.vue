<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j4__6ibfh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j4__6ibfh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:rewind-45" /></template>

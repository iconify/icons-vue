<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w0jsjpboj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w0jsjpboj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:toy-brick-minus-outline" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l88_q8bvd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l88_q8bvd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:stanley-knife" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g9fmcab0k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g9fmcab0k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:tag-plus" /></template>

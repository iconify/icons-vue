<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sx7e35btp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="sx7e35btp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:night-cloudy-windy" /></template>

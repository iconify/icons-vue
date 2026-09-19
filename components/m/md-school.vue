<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rtyhg7ndl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rtyhg7ndl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-school" /></template>

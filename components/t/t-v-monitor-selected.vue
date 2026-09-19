<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/addk9z6wr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="addk9z6wr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:t-v-monitor-selected" /></template>

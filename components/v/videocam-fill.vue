<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dsx7mlbfl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="dsx7mlbfl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:videocam-fill" /></template>

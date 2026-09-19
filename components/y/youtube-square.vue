<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w4oogcjvx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1536};
const content = `<path class="w4oogcjvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:youtube-square" /></template>

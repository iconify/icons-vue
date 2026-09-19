<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kunmh0bwu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="kunmh0bwu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fad:microphone" /></template>

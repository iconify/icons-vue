<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pzw32fbms.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1536};
const content = `<path class="pzw32fbms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:twitter-square" /></template>

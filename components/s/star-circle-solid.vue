<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a7k6-lm3u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="a7k6-lm3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:star-circle-solid" /></template>

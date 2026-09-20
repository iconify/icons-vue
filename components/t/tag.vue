<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yf1ycbcru.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="yf1ycbcru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:tag" /></template>

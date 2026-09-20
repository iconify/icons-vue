<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wvobarqgj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wvobarqgj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:search-zoom-out2-filled" /></template>

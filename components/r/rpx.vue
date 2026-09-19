<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iedl4rwbd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="iedl4rwbd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:rpx" /></template>

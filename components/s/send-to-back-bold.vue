<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t7flwxcck.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="t7flwxcck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:send-to-back-bold" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p76hqtbzi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p76hqtbzi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:the-red-yeti" /></template>

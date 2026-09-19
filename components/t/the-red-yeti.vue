<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vx0k6uber.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="vx0k6uber"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:the-red-yeti" /></template>

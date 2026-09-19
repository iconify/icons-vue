<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vi9qqdnqh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vi9qqdnqh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:vk" /></template>

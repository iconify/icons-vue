<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w03ix6lll.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":286,"height":512};
const content = `<path class="w03ix6lll"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:pogoscript" /></template>

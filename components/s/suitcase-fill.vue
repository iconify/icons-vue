<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bmo9kkbqh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bmo9kkbqh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:suitcase-fill" /></template>

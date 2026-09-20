<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lq6pfdcca.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="lq6pfdcca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:strikethrough-a" /></template>

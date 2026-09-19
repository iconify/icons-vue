<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vyf9mq7mm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vyf9mq7mm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:wastebasket" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t62z6ibns.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="t62z6ibns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:surf-20" /></template>

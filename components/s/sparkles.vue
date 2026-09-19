<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wd7v1qbfs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wd7v1qbfs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:sparkles" /></template>

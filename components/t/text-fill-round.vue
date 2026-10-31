<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k56d62gzl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k56d62gzl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:text-fill-round" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pihu-0nzh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pihu-0nzh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:vitest" /></template>

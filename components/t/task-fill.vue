<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gyy_pbcwl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gyy_pbcwl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:task-fill" /></template>

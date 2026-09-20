<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f__wo6bdr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f__wo6bdr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:wine" /></template>

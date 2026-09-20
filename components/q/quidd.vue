<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/omkiu1b3l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="omkiu1b3l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:quidd" /></template>

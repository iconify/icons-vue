<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ie2opebeh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ie2opebeh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:step-backward" /></template>

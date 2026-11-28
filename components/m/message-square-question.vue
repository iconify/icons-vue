<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cvh0v82tz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cvh0v82tz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:message-square-question" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g-l9c4vor.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g-l9c4vor"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:x-triangle" /></template>

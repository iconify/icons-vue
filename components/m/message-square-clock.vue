<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bsfg5ubrl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bsfg5ubrl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:message-square-clock" /></template>

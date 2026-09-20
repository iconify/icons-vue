<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ep-jsbg9z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ep-jsbg9z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:shield-line" /></template>

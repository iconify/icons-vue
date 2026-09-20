<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dlifvbe-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dlifvbe-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:virus-fill" /></template>

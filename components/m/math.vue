<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rwoutw7cj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rwoutw7cj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:math" /></template>

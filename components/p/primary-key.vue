<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xygd24b4q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xygd24b4q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:primary-key" /></template>

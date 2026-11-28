<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mq4uxb9up.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mq4uxb9up"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:minimize" /></template>

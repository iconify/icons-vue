<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s7a929bds.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s7a929bds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:park-fill" /></template>

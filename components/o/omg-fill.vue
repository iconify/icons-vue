<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x-qkcjb6e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x-qkcjb6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:omg-fill" /></template>

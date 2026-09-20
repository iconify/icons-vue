<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/en96x3gyh.css';
import '../../css/h/h68a5vtzz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="en96x3gyh"/><circle class="h68a5vtzz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:status-list" /></template>

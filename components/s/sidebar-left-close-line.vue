<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tfu8o6blj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tfu8o6blj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:sidebar-left-close-line" /></template>

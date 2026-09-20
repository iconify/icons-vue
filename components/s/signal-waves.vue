<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wpuf4oy7f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wpuf4oy7f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:signal-waves" /></template>

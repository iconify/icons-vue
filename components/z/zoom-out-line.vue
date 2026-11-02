<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h-a4dyv4m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h-a4dyv4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:zoom-out-line" /></template>

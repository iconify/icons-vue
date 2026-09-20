<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt2orlbgf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dt2orlbgf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:rewind-forward-square-10-fill" /></template>

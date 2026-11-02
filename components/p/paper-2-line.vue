<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hmo28tb6b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hmo28tb6b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:paper-2-line" /></template>

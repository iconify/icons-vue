<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/th_q9jbly.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="th_q9jbly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:text-area-fill" /></template>

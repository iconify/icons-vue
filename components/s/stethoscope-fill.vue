<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w_-lpjk0t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w_-lpjk0t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:stethoscope-fill" /></template>

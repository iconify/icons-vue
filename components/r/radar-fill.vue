<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m3_ta5b5e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m3_ta5b5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:radar-fill" /></template>

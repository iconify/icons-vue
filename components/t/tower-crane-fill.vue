<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x908zntiy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x908zntiy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:tower-crane-fill" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vt5qnsbss.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vt5qnsbss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:qq-line" /></template>

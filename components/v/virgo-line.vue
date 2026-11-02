<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e3ch4dbjl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e3ch4dbjl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:virgo-line" /></template>

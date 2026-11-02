<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f15g3fbrn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f15g3fbrn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:refresh-2-line" /></template>

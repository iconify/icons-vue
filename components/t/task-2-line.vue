<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3klf5b_b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v3klf5b_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:task-2-line" /></template>

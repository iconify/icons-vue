<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lkatfdcit.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lkatfdcit"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:za-sort-ascending-letters-fill" /></template>

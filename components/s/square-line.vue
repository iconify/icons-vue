<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kuogy9mlk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kuogy9mlk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:square-line" /></template>

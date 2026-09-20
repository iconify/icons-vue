<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/ml8f8msdh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ml8f8msdh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:medium-fill" /></template>

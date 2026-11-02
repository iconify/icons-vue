<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k_1nlibzu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k_1nlibzu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:switch-fill" /></template>

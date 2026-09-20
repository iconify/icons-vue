<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e11y7_kzu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e11y7_kzu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:plotly" /></template>

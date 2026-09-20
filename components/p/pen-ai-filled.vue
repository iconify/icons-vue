<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k3s9o7byd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k3s9o7byd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:pen-ai-filled" /></template>

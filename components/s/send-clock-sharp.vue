<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lejfyq1sj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lejfyq1sj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:send-clock-sharp" /></template>

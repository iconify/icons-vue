<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e6elb8b9h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e6elb8b9h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:process-line" /></template>

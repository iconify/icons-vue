<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lf7v7crei.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lf7v7crei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:notification-off-fill" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t7z_3tbvj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t7z_3tbvj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:memory-stick-fill" /></template>

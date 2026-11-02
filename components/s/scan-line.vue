<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lr6tnccry.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lr6tnccry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:scan-line" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ea-b2cc9b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ea-b2cc9b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:signature-2-line" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rdxef9m6b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rdxef9m6b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:strikethrough-fill" /></template>

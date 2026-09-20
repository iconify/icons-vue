<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/euw5bu_9k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="euw5bu_9k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:user-warning-line" /></template>

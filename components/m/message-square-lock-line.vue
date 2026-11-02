<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kku6257la.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kku6257la"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:message-square-lock-line" /></template>

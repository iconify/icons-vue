<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tqkc3tacr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tqkc3tacr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:message-circle-heart-fill" /></template>

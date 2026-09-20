<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xql-uobud.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xql-uobud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:transfer-4-line" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gh09i1btx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gh09i1btx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:transfer-3-fill" /></template>

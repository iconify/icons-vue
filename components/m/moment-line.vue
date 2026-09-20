<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tbm6ne5it.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tbm6ne5it"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:moment-line" /></template>

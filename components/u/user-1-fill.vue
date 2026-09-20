<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eqi00l9tb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eqi00l9tb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:user-1-fill" /></template>

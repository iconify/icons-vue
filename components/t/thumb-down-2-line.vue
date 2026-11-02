<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hus9mwmym.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hus9mwmym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:thumb-down-2-line" /></template>

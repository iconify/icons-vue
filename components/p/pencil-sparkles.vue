<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h_f36pb9p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h_f36pb9p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:pencil-sparkles" /></template>

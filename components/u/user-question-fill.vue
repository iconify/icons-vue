<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pnhckg2ax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pnhckg2ax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:user-question-fill" /></template>

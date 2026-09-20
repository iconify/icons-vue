<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ym5qnl2lw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ym5qnl2lw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:web-fill" /></template>

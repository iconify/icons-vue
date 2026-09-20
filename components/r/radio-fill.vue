<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i6c0x_jlb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i6c0x_jlb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:radio-fill" /></template>

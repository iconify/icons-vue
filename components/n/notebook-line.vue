<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ffvya_hzp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ffvya_hzp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:notebook-line" /></template>

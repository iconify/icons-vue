<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vlhd07b4m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vlhd07b4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:moon-fill" /></template>

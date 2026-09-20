<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k4y3y7xtl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k4y3y7xtl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:telegram-alt" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wpjy7rbvl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wpjy7rbvl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:toggle-left-2-fill" /></template>

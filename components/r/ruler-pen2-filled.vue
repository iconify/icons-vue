<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fzqhjqb3t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fzqhjqb3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:ruler-pen2-filled" /></template>

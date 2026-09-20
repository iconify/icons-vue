<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ctg0mn-rs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ctg0mn-rs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:mail-send-reply-all-flat" /></template>

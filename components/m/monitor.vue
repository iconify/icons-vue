<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e60u6gbnf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e60u6gbnf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:monitor" /></template>

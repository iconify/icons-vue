<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yhae6cciv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yhae6cciv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:sparkles-3-fill" /></template>

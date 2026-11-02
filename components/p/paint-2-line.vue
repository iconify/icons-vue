<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y3zer8wif.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y3zer8wif"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:paint-2-line" /></template>

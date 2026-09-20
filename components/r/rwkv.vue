<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i39915bhr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i39915bhr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:rwkv" /></template>

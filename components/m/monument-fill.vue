<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sjlgfhysb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sjlgfhysb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:monument-fill" /></template>

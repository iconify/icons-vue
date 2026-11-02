<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mo8zr4c7m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mo8zr4c7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:ubuntu-line" /></template>

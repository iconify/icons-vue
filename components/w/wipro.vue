<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/th4livb8h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="th4livb8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:wipro" /></template>

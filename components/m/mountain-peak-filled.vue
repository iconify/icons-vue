<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j55ox3b6s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j55ox3b6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:mountain-peak-filled" /></template>

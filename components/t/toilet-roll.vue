<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gdkeixbmd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gdkeixbmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:toilet-roll" /></template>

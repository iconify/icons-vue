<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hjk-647jr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hjk-647jr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:user-check" /></template>

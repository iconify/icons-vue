<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hf1tdzwrn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hf1tdzwrn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:stadium" /></template>

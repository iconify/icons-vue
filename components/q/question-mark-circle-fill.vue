<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i5s7e3c_m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i5s7e3c_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:question-mark-circle-fill" /></template>

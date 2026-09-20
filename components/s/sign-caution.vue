<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vehn28bzm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vehn28bzm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:sign-caution" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dfxaz2nik.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dfxaz2nik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:reddit-2-fill" /></template>

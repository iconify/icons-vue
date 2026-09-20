<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lgah6znzj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lgah6znzj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:netlify" /></template>

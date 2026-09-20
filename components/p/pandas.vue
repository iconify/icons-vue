<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m30tcab1z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m30tcab1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:pandas" /></template>

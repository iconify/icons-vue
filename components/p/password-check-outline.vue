<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/os-g09bge.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="os-g09bge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:password-check-outline" /></template>

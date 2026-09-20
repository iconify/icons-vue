<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/erio8bbjo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="erio8bbjo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:pill" /></template>

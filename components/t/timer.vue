<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c6b6ttbiz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c6b6ttbiz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:timer" /></template>

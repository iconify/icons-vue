<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e00v7ofcu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e00v7ofcu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:pointer-off" /></template>

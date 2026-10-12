<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h1ooaw6hj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h1ooaw6hj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:refrigerator-filled" /></template>

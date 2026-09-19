<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ielc4mb8x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ielc4mb8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:trash" /></template>

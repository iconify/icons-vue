<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uor3t-b2m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uor3t-b2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:note-book" /></template>

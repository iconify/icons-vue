<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pw7c98bqz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pw7c98bqz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:pi" /></template>

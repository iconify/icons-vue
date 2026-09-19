<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ucu8i8bat.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ucu8i8bat"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:water-filled" /></template>

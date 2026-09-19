<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c9bxnbeju.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c9bxnbeju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:size-distort-filled" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d55dhypbp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d55dhypbp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:minimize" /></template>

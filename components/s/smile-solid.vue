<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nuz5b1zvg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nuz5b1zvg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:smile-solid" /></template>

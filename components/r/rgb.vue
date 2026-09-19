<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w_uw5r6dy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w_uw5r6dy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:rgb" /></template>

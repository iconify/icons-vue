<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w27-8wbtm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w27-8wbtm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:torch-filled" /></template>

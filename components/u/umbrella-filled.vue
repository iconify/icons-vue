<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mt0vp4b4j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mt0vp4b4j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:umbrella-filled" /></template>

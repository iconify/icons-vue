<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yd3j_obfm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yd3j_obfm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:umbrella-fill-round" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ka84vzb2a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="ka84vzb2a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:whatsapp" /></template>

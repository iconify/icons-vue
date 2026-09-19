<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l_8a0ebkt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="l_8a0ebkt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:whatsapp" /></template>

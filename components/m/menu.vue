<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fd6vyq9rg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":384};
const content = `<path class="fd6vyq9rg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:menu" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ngt-l5hup.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="ngt-l5hup"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:turtle-bold" /></template>

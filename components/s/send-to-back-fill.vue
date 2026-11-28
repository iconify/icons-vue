<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vaq1hab2x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="vaq1hab2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:send-to-back-fill" /></template>

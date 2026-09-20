<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iq13j2e4j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="iq13j2e4j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:vine" /></template>

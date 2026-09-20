<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o_v5ysu5x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="o_v5ysu5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:phone" /></template>

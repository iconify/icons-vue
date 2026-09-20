<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u62_66b0f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path class="u62_66b0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:ruler-pen" /></template>

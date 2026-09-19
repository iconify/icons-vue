<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eeo8jg0ef.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eeo8jg0ef"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:terminal-filled" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u81g_fbjz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":82,"height":26};
const content = `<path class="u81g_fbjz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:wordmark-support-26" /></template>

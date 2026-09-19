<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cr0e94jng.css';
import '../../css/u/uixwhfcch.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="cr0e94jng"/><path class="uixwhfcch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:mobile-signal" /></template>

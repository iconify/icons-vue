<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/thgsep5_e.css';
import '../../css/i/ift-4msrf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="thgsep5_e"/><path class="ift-4msrf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:text-creation" /></template>

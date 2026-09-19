<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vn78bu-1w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vn78bu-1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:skillshare" /></template>

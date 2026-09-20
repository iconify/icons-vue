<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/epncsdd1e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="epncsdd1e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:trmnl-dark" /></template>

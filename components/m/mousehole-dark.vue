<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bfh8-9bxl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bfh8-9bxl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:mousehole-dark" /></template>

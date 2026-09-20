<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/er6f_gbdr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="er6f_gbdr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:optistack-light" /></template>

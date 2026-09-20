<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j5b2u6byf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j5b2u6byf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ring-light" /></template>

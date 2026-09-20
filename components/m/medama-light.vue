<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ouj21t23v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ouj21t23v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:medama-light" /></template>

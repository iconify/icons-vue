<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q7_289hqs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":384};
const content = `<path class="q7_289hqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:storage" /></template>

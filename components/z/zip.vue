<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tsyg74b0d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tsyg74b0d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:zip" /></template>

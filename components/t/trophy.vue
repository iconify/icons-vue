<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv37jub_b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sv37jub_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:trophy" /></template>

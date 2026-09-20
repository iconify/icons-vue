<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e6qryzp-n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="e6qryzp-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:star-and-crescent" /></template>

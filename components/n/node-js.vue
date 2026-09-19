<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kv6d6372h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="kv6d6372h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:node-js" /></template>

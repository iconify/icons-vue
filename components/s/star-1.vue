<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sa8kv5a7s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sa8kv5a7s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:star-1" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w8udhfbrq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="w8udhfbrq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-boarding-kids-train-on-railway-track" /></template>

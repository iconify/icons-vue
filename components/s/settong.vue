<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xnjlkttce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xnjlkttce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:settong" /></template>

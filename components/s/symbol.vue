<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d_4ensb5v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="d_4ensb5v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:symbol" /></template>

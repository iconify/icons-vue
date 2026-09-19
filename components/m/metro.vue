<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/va_mebb_q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1025};
const content = `<path class="va_mebb_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:metro" /></template>

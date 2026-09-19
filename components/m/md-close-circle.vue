<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vwx53kb4s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vwx53kb4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-close-circle" /></template>

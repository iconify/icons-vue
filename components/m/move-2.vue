<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gd4oy6b3s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gd4oy6b3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:move-2" /></template>

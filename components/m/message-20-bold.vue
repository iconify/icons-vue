<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d-vg6lr_s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="d-vg6lr_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:message-20-bold" /></template>

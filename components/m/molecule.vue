<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xq6p72bht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xq6p72bht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:molecule" /></template>

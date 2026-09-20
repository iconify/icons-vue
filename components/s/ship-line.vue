<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sarag4mkf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sarag4mkf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:ship-line" /></template>

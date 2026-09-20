<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d0zs48c_s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d0zs48c_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:rewind-mini-fill" /></template>

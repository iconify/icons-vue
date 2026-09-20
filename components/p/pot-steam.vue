<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2ne6ab_s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d2ne6ab_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:pot-steam" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p1m_nbbzf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":320,"height":512};
const content = `<path class="p1m_nbbzf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="academicons:piazza" /></template>

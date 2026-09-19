<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/og-oztl2v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="og-oztl2v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:reddit-alien" /></template>

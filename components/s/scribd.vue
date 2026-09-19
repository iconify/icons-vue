<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/frb1tob9r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="frb1tob9r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:scribd" /></template>

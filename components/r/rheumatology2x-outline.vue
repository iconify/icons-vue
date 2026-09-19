<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f2mmnacuz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="f2mmnacuz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:rheumatology2x-outline" /></template>

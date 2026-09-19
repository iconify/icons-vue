<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q-001pbgd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1792};
const content = `<path class="q-001pbgd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:user-circle" /></template>

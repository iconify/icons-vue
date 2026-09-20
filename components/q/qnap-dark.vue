<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vg_08ysvz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vg_08ysvz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:qnap-dark" /></template>

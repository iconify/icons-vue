<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f1u2uwnio.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":512};
const content = `<path class="f1u2uwnio"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:puzzle" /></template>

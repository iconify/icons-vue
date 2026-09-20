<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/md2-6kbtb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="md2-6kbtb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:netbird-light" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rod79qbyt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rod79qbyt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:matter-dark" /></template>

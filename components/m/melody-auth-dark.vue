<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iqppkb4wy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="iqppkb4wy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:melody-auth-dark" /></template>

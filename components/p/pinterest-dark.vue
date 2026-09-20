<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d_m9zcc1m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="d_m9zcc1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pinterest-dark" /></template>

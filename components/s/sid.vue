<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yasl903_y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yasl903_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:sid" /></template>

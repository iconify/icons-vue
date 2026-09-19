<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c-7lnjbeu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":432};
const content = `<path class="c-7lnjbeu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:pause-circle-outline" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dpfa0s5nb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dpfa0s5nb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:qemu-light" /></template>

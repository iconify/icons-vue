<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oymyhruay.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="oymyhruay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:pause-1" /></template>

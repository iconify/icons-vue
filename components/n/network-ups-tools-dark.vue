<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x1r2axovm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="x1r2axovm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:network-ups-tools-dark" /></template>

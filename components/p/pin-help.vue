<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hcni0tkfb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":456};
const content = `<path class="hcni0tkfb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:pin-help" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xxsb-cc6n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xxsb-cc6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:waze" /></template>

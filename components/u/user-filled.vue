<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tyw10oeoa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tyw10oeoa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:user-filled" /></template>

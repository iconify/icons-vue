<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gzpy4zb0x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="gzpy4zb0x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:shift" /></template>

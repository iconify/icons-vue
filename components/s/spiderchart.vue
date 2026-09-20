<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p3awb6ryc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="p3awb6ryc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:spiderchart" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y92m0cfbr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":368,"height":384};
const content = `<path class="y92m0cfbr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:view-array" /></template>

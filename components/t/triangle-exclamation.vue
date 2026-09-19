<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h8zp1_bsn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="h8zp1_bsn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:triangle-exclamation" /></template>

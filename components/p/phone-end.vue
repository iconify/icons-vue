<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xc22_bkfi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":384};
const content = `<path class="xc22_bkfi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:phone-end" /></template>

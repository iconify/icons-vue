<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ngt13rb5c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":432};
const content = `<path class="ngt13rb5c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:nfc" /></template>

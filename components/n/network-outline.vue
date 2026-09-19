<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nygshlbxp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":432};
const content = `<path class="nygshlbxp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:network-outline" /></template>

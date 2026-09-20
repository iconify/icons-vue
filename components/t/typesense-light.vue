<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xfv2j2qkp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xfv2j2qkp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:typesense-light" /></template>

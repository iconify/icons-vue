<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xdnv-n33c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xdnv-n33c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:snapdrop-dark" /></template>

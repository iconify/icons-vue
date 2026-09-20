<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zydp2p7fp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zydp2p7fp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:receipt-wrangler-light" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uqyvu54rg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uqyvu54rg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:twake-drive-dark" /></template>

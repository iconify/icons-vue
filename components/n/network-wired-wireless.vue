<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t5tv27bcp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="t5tv27bcp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:network-wired-wireless" /></template>

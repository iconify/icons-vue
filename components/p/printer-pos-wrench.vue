<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ct8u88f6o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ct8u88f6o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:printer-pos-wrench" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xzbqii5ig.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xzbqii5ig"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:printer-check" /></template>

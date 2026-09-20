<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jes81sbzq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jes81sbzq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:printer-point-of-sale-sync" /></template>

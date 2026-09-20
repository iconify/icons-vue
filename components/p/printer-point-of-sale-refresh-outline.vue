<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ynbx3b35w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ynbx3b35w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:printer-point-of-sale-refresh-outline" /></template>

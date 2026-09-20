<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s6d6_jbsq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s6d6_jbsq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:shipping-pallet" /></template>

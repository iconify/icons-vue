<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xducvmk_t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="xducvmk_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:travel-hotel-pool-ladder-2-pool-stairs-swim-swimming-water-ladder" /></template>

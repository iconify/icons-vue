<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ei56k7b1w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ei56k7b1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:money-bill-wheat" /></template>

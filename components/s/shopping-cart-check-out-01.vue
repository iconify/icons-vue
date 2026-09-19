<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cxp457pzx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cxp457pzx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:shopping-cart-check-out-01" /></template>

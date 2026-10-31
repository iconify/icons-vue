<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lp_01h4ee.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lp_01h4ee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:shopping-cart-fill-round" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lnvx83ber.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lnvx83ber"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mi:shopping-cart-add" /></template>

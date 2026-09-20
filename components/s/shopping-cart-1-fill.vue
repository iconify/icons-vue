<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sddatub1j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sddatub1j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:shopping-cart-1-fill" /></template>

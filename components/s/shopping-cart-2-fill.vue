<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lnaeqbc0x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lnaeqbc0x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:shopping-cart-2-fill" /></template>

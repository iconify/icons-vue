<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ydda9xosv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ydda9xosv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:shopping-cart-solid" /></template>

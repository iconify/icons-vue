<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mydz6fg-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mydz6fg-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:shopping-cart-2-fill" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/ht-g1lbxx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":456};
const content = `<path class="ht-g1lbxx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:shopping-cart-add" /></template>

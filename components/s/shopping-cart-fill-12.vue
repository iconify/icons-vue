<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ypg_y81bx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="ypg_y81bx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:shopping-cart-fill-12" /></template>

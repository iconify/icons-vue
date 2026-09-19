<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p0om-1r6q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p0om-1r6q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:shopping-cart-solid" /></template>

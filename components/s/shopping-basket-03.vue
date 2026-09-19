<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f78d57bsq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f78d57bsq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:shopping-basket-03" /></template>

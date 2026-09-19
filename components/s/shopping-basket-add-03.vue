<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yccolbbcz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yccolbbcz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:shopping-basket-add-03" /></template>

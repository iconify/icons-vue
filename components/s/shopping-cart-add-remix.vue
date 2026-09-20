<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x8kbu62ly.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x8kbu62ly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:shopping-cart-add-remix" /></template>

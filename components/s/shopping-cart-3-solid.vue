<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ouae63yvr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ouae63yvr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:shopping-cart-3-solid" /></template>

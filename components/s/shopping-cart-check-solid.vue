<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/umahpab1k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="umahpab1k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:shopping-cart-check-solid" /></template>

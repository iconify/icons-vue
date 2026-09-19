<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c6nx8fehg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="c6nx8fehg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:shopping-cart-outline" /></template>

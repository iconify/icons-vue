<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r8kdgp8jj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="r8kdgp8jj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:shopping-cart-subtract-remix" /></template>

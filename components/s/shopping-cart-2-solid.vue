<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/awmk39b_n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="awmk39b_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:shopping-cart-2-solid" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dad1_xhcg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dad1_xhcg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:shopping-bag-hand-bag-price-tag-solid" /></template>

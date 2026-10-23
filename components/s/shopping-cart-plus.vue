<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rnk9c6m_g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rnk9c6m_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:shopping-cart-plus" /></template>

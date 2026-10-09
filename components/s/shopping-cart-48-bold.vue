<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ix_lw37hq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ix_lw37hq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:shopping-cart-48-bold" /></template>

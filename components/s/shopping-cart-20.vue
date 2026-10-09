<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kl3m84wvd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="kl3m84wvd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:shopping-cart-20" /></template>

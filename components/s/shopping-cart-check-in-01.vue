<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c2o6gfb2p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c2o6gfb2p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:shopping-cart-check-in-01" /></template>

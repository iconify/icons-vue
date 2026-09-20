<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jfc4w3bvk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jfc4w3bvk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:shopping-cart-2-line" /></template>

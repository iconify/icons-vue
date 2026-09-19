<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aycs3t8th.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="aycs3t8th"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:shopping-cart-solid" /></template>

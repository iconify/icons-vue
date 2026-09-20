<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ehrgniblw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ehrgniblw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:shopping-cart-solid" /></template>

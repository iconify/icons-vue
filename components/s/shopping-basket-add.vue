<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e7qb-gbjk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="e7qb-gbjk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:shopping-basket-add" /></template>

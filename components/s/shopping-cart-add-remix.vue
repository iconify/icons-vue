<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipmir7btz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ipmir7btz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:shopping-cart-add-remix" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ooj_07b2k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ooj_07b2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:shopping-cart-add" /></template>

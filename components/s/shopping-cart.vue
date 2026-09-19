<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/up3p33-bz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="up3p33-bz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:shopping-cart" /></template>

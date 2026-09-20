<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cn47a8a2v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="cn47a8a2v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:shopping-cart-add-solid" /></template>
